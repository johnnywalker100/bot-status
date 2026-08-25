# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8813** (-11.87% since start) |
| Peak / drawdown | 1.0141 / -13.10% |
| Ticks recorded | 777 |
| Last tick | 2026-08-25T15:08:27.330623+00:00 (+0.0070%) |
| Risk rails | brake: drawdown -13.1% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-25 14:00:00+00:00) |
| Gross leverage | 0.27x |
| Weeks tracked | 5 |
| Average week | -0.94% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.66% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.3% | +1 |
| SOL perp | +5.6% | +1 |
| BCH perp | +3.0% | +1 |
| DOT perp | +3.0% | +3 |
| ETH perp | +2.8% | +1 |
| AVAX perp | +2.5% | +3 |
| ADA perp | +2.4% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
