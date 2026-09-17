# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8721** (-12.79% since start) |
| Peak / drawdown | 1.0141 / -14.01% |
| Ticks recorded | 1321 |
| Last tick | 2026-09-17T10:08:29.857366+00:00 (-0.0748%) |
| Risk rails | brake: drawdown -14.0% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-17 09:00:00+00:00) |
| Gross leverage | 0.29x |
| Weeks tracked | 8 |
| Average week | -0.71% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| DOT perp | +5.8% | +5 |
| SOL perp | +5.7% | +1 |
| AVAX perp | +4.3% | +5 |
| ETH perp | +2.8% | +1 |
| BCH perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.6% | -1 |
| LTC perp | -3.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
