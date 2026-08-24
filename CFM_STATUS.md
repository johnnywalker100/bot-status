# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8916** (-10.84% since start) |
| Peak / drawdown | 1.0141 / -12.08% |
| Ticks recorded | 760 |
| Last tick | 2026-08-24T22:08:12.968927+00:00 (-0.0988%) |
| Risk rails | brake: drawdown -12.0% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-24 21:00:00+00:00) |
| Gross leverage | 0.21x |
| Weeks tracked | 5 |
| Average week | -0.71% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.52% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.5% | +1 |
| BCH perp | +3.1% | +1 |
| DOT perp | +3.0% | +3 |
| ETH perp | +2.8% | +1 |
| AVAX perp | +2.5% | +3 |
| ADA perp | +2.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
