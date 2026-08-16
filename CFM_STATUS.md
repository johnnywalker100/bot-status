# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9137** (-8.63% since start) |
| Peak / drawdown | 1.0141 / -9.90% |
| Ticks recorded | 547 |
| Last tick | 2026-08-16T00:08:38.837007+00:00 (+0.7675%) |
| Risk rails | normal (dd -9.9%) |
| Data source | coinbase-cfm (bar 2026-08-15 23:00:00+00:00) |
| Gross leverage | 2.84x |
| Weeks tracked | 3 |
| Average week | -0.37% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.62% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.6% | +5 |
| XLM perp | +17.3% | +2 |
| AVAX perp | +7.5% | +11 |
| BCH perp | +6.7% | +3 |
| ETH perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.0% | -10 |
| NEAR perp | -35.4% | -4 |
| BTC perp | -34.5% | -5 |
| LTC perp | -33.8% | -14 |
| BNB perp | -26.6% | -4 |
| LINK perp | -20.7% | -4 |
| ZEC perp | -10.7% | -2 |
| ADA perp | -9.7% | -5 |
| DOT perp | -8.3% | -10 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
