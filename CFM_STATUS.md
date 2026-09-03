# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8819** (-11.81% since start) |
| Peak / drawdown | 1.0141 / -13.04% |
| Ticks recorded | 997 |
| Last tick | 2026-09-03T20:08:32.284678+00:00 (-0.0086%) |
| Risk rails | brake: drawdown -13.0% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-03 19:00:00+00:00) |
| Gross leverage | 0.10x |
| Weeks tracked | 6 |
| Average week | -0.77% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +6.0% | +1 |
| AVAX perp | +2.6% | +3 |
| DOT perp | +1.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
