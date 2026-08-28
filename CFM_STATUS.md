# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8794** (-12.06% since start) |
| Peak / drawdown | 1.0141 / -13.28% |
| Ticks recorded | 853 |
| Last tick | 2026-08-28T19:08:20.173419+00:00 (-0.0158%) |
| Risk rails | brake: drawdown -13.3% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-28 18:00:00+00:00) |
| Gross leverage | 0.12x |
| Weeks tracked | 5 |
| Average week | -0.98% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.87% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BCH perp | +2.8% | +1 |
| ETH perp | +2.8% | +1 |
| DOT perp | +1.9% | +2 |
| AVAX perp | +1.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -2.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
