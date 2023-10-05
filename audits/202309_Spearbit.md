# 2023-09 Spearbit Security Audit

## Audit Dates

Sept. 6th - Sept. 12th, 2023

## Audit Scope

The technical upgrade to the TLC contract includes the addition of a Global Unlocking parameter, which enables TLC unlocking schedules to be set such that 12 months from the TLC contract upgrade, tokens begin unlocking 1/24th per month for 24 months.

There are also two minor updates:
- added `getRiver()` view function to `RedeemManager`.
- added `setOperatorStoppedValidatorCount` event. 

## Audit Summary

|    **Severity**   | **Count** | **Fixed** | **Acknowledged** |
|:-----------------:|:---------:|:---------:|:----------------:|
|   Critical Risk   |     0     |     0     |         0        |
|     High Risk     |     0     |     0     |         0        |
|    Medium Risk    |     0     |     0     |         0        |
|      Low risk     |     5     |     4     |         1        |
| Gas Optimizations |     2     |     2     |         0        |
|   Informational   |     5     |     4     |         1        |
|     **Total**     |     12    |     10     |         2        |

## Security Researchers

[![](https://github.com/optimumsec.png?size=50)](https://github.com/optimumsec) [![](https://github.com/Saw-mon-and-Natalie.png?size=50)](https://github.com/Saw-mon-and-Natalie) [![](https://github.com/xiaoming9090.png?size=50)](https://github.com/xiaoming9090) [Ellahinator](https://github.com/Ellahinator)

## Audit Report

See [full report](https://github.com/spearbit/portfolio/blob/master/pdfs/LiquidCollectivePR-Spearbit-Security-Review-Sept.pdf) for more details.
