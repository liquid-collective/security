# 2024-02 Certora Security Audit & Formal Verification

## Audit Dates

December 3rd, 2023 -> February 8th, 2024.

## Audit Scope

Full protocol audit including all smart contracts as per commit [0b15fbfa36af17c1f5e8059de40c2de325210204](https://github.com/liquid-collective/liquid-collective-protocol/commit/0b15fbfa36af17c1f5e8059de40c2de325210204)

It covers the following smart contracts & all the contracts that they inherit:
- River
- Oracle
- Allowlist
- Withdraw
- ELFeeRecipient
- WLSETH
- Firewall
- TUPProxy
- Initializable
- TLC
- OperatorsRegistry
- CoverageFund
- Administrable
- RedeemManager

## Audit Summary

|    **Severity**   | **Count** | **Fixed** | **Acknowledged** |
|:-----------------:|:---------:|:---------:|:----------------:|
|   Critical Risk   |     1     |     1     |         1        |
|     High Risk     |     2     |     2     |         1        |
|    Medium Risk    |     4     |     4     |         2        |
|      Low risk     |     5     |     4     |         2        |
|   Informational   |     3     |     3     |         1        |
|     **Total**     |     15    |     14    |         7        |

## Audit Report

See [Certora's full report](https://www.certora.com/reports/alluvialfinance-liquidcollective) for more details.
