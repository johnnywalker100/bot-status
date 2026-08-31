# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8783** (-12.17% since start) |
| Peak / drawdown | 1.0141 / -13.39% |
| Ticks recorded | 919 |
| Last tick | 2026-08-31T14:08:31.985601+00:00 (-0.0299%) |
| Risk rails | brake: drawdown -13.4% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-31 13:00:00+00:00) |
| Gross leverage | 0.15x |
| Weeks tracked | 6 |
| Average week | -0.84% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +5.8% | +1 |
| ETH perp | +2.8% | +1 |
| AVAX perp | +2.4% | +3 |
| DOT perp | +1.9% | +2 |

| Short | Size | Contracts |
|---|---|---|
| ADA perp | -2.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
