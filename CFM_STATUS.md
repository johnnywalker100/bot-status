# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8880** (-11.20% since start) |
| Peak / drawdown | 1.0141 / -12.44% |
| Ticks recorded | 718 |
| Last tick | 2026-08-23T04:08:51.100138+00:00 (-0.9238%) |
| Risk rails | brake: drawdown -12.4% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-23 03:00:00+00:00) |
| Gross leverage | 0.25x |
| Weeks tracked | 4 |
| Average week | -0.98% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.98% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +6.9% | +1 |
| SOL perp | +5.2% | +1 |
| BCH perp | +3.1% | +1 |
| DOT perp | +3.0% | +3 |
| ETH perp | +2.7% | +1 |
| ADA perp | +2.5% | +1 |
| AVAX perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
