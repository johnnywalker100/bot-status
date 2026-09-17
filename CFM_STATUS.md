# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8717** (-12.83% since start) |
| Peak / drawdown | 1.0141 / -14.04% |
| Ticks recorded | 1319 |
| Last tick | 2026-09-17T08:08:50.639623+00:00 (-0.0516%) |
| Risk rails | brake: drawdown -14.0% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-17 07:00:00+00:00) |
| Gross leverage | 0.29x |
| Weeks tracked | 8 |
| Average week | -0.72% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| DOT perp | +5.8% | +5 |
| SOL perp | +5.7% | +1 |
| AVAX perp | +4.3% | +5 |
| ETH perp | +2.8% | +1 |
| BCH perp | +2.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.7% | -1 |
| LTC perp | -3.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
