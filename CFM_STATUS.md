# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9640** (-3.60% since start) |
| Peak / drawdown | 1.0141 / -4.94% |
| Ticks recorded | 1537 |
| Last tick | 2026-09-26T13:08:10.872859+00:00 (-0.0986%) |
| Risk rails | normal (dd -4.9%) |
| Data source | coinbase-cfm (bar 2026-09-26 12:00:00+00:00) |
| Gross leverage | 0.87x |
| Weeks tracked | 9 |
| Average week | +0.51% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.0% | +1 |
| DOT perp | +11.5% | +9 |
| ETH perp | +11.2% | +4 |
| AAVE perp | +8.0% | +1 |
| AVAX perp | +7.9% | +7 |
| LINK perp | +7.4% | +1 |
| BCH perp | +7.0% | +2 |
| SOL perp | +6.3% | +1 |
| LTC perp | +3.8% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
