# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8919** (-10.81% since start) |
| Peak / drawdown | 1.0141 / -12.05% |
| Ticks recorded | 1351 |
| Last tick | 2026-09-18T16:08:45.375356+00:00 (+0.0390%) |
| Risk rails | brake: drawdown -12.0% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-18 15:00:00+00:00) |
| Gross leverage | 0.32x |
| Weeks tracked | 8 |
| Average week | -0.43% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.70% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| LINK perp | +6.8% | +1 |
| SOL perp | +6.2% | +1 |
| DOT perp | +5.1% | +4 |
| AVAX perp | +4.5% | +5 |
| ETH perp | +2.9% | +1 |
| BCH perp | +2.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -3.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
