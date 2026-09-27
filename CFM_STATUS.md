# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9813** (-1.87% since start) |
| Peak / drawdown | 1.0141 / -3.23% |
| Ticks recorded | 1557 |
| Last tick | 2026-09-27T09:08:21.616986+00:00 (-0.5925%) |
| Risk rails | normal (dd -3.2%) |
| Data source | coinbase-cfm (bar 2026-09-27 08:00:00+00:00) |
| Gross leverage | 0.96x |
| Weeks tracked | 9 |
| Average week | +0.72% |
| Weeks >= +3% | 22% |
| Best / worst week | +6.78% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.8% | +1 |
| DOT perp | +11.5% | +9 |
| ETH perp | +11.0% | +4 |
| BTC perp | +8.6% | +1 |
| AVAX perp | +8.0% | +7 |
| AAVE perp | +7.9% | +1 |
| LINK perp | +7.3% | +1 |
| BCH perp | +6.9% | +2 |
| SOL perp | +6.3% | +1 |
| LTC perp | +3.7% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
