# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8797** (-12.03% since start) |
| Peak / drawdown | 1.0141 / -13.25% |
| Ticks recorded | 1027 |
| Last tick | 2026-09-05T03:08:31.561397+00:00 (-0.0005%) |
| Risk rails | brake: drawdown -13.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-05 02:00:00+00:00) |
| Gross leverage | 0.11x |
| Weeks tracked | 6 |
| Average week | -0.81% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +5.8% | +1 |
| AVAX perp | +3.4% | +4 |
| DOT perp | +2.0% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
