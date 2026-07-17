# 2026-03 Certora Security Audit

## Audit Dates

February 26th, 2026 -> March 16th, 2026.

## Audit Scope

Differential audit of the Liquid Collective Protocol as per commit [dbcec79986](https://github.com/liquid-collective/liquid-collective-protocol/commit/dbcec79986) with final review at commit [964f0e363f](https://github.com/liquid-collective/liquid-collective-protocol/commit/964f0e363f).

The audit focused on the following changes:
- Refactor of the validator allocation selection logic across `OperatorsRegistryV1`, `RiverV1`, and `ConsensusLayerDepositManagerV1`, moving from a count-based approach to an explicit operator allocation model where allocations specify how many validators each operator should provide (BYOV)
- Validator exit mechanism was updated from a count-based approach to an explicit operator allocation model where allocations specify how many validators each operator should exit (BYOV)
- Contracts were upgraded to Solidity 0.8.33
- Unnecessary `unchecked { ++i; }` were removed
- Loop increments were moved to declaration for better readability

It covers the following smart contracts & all the contracts that they inherit:
- Administrable
- Allowlist
- CoverageFund
- ELFeeRecipient
- Firewall
- Initializable
- OperatorsRegistry
- Oracle
- ProtocolMetrics
- RedeemManager
- River
- TUPProxy
- Withdraw

Out of scope:
- `contracts/src/l2-token`
- `contracts/src/TLC.1.sol`
- `contracts/src/migration`
- `contracts/src/WLSETH.1.sol`

## Audit Summary

|    **Severity**   | **Count** | **Fixed** | **Acknowledged** |
|:-----------------:|:---------:|:---------:|:----------------:|
|   Critical Risk   |     0     |     0     |         0        |
|     High Risk     |     1     |     1     |         0        |
|    Medium Risk    |     2     |     1     |         1        |
|      Low Risk     |     4     |     2     |         2        |
|   Informational   |     2     |     1     |         1        |
|     **Total**     |     9     |     5     |         4        |

## Audit Report

See [Certora's full report](https://github.com/liquid-collective/liquid-collective-protocol/blob/main/audits/certora/202603_Certora.pdf) for more details.
