# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8899** (-11.01% since start) |
| Peak / drawdown | 1.0141 / -12.25% |
| Ticks recorded | 1349 |
| Last tick | 2026-09-18T14:08:51.842473+00:00 (+0.4323%) |
| Risk rails | brake: drawdown -12.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-18 13:00:00+00:00) |
| Gross leverage | 0.31x |
| Weeks tracked | 8 |
| Average week | -0.46% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.47% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| LINK perp | +6.7% | +1 |
| SOL perp | +6.1% | +1 |
| DOT perp | +5.1% | +4 |
| AVAX perp | +4.5% | +5 |
| ETH perp | +2.9% | +1 |
| BCH perp | +2.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -3.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
