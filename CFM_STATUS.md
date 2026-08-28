# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8790** (-12.10% since start) |
| Peak / drawdown | 1.0141 / -13.32% |
| Ticks recorded | 855 |
| Last tick | 2026-08-28T22:08:18.225292+00:00 (-0.0379%) |
| Risk rails | brake: drawdown -13.3% <= -12%, half size; blind 2.0h -> 50% size on resume |
| Data source | coinbase-cfm (bar 2026-08-28 21:00:00+00:00) |
| Gross leverage | 0.02x |
| Weeks tracked | 5 |
| Average week | -0.99% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.91% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| DOT perp | +1.0% | +1 |
| AVAX perp | +0.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
