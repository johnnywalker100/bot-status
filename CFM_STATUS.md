# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9637** (-3.63% since start) |
| Peak / drawdown | 1.0141 / -4.97% |
| Ticks recorded | 1458 |
| Last tick | 2026-09-23T05:08:26.054234+00:00 (-0.1094%) |
| Risk rails | normal (dd -5.0%) |
| Data source | coinbase-cfm (bar 2026-09-23 04:00:00+00:00) |
| Gross leverage | 0.98x |
| Weeks tracked | 9 |
| Average week | +0.51% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.8% | +1 |
| XLM perp | +11.5% | +1 |
| DOT perp | +11.1% | +9 |
| BNB perp | +8.2% | +1 |
| AAVE perp | +7.7% | +1 |
| BCH perp | +7.0% | +2 |
| LINK perp | +6.8% | +1 |
| SOL perp | +6.2% | +1 |
| AVAX perp | +5.8% | +5 |
| ETH perp | +5.8% | +2 |
| DOGE perp | +5.3% | +1 |
| LTC perp | +3.3% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
