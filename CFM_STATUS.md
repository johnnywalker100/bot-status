# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9238** (-7.62% since start) |
| Peak / drawdown | 1.0141 / -8.90% |
| Ticks recorded | 476 |
| Last tick | 2026-08-13T00:08:28.948465+00:00 (-0.9682%) |
| Risk rails | normal (dd -8.9%) |
| Data source | coinbase-cfm (bar 2026-08-12 23:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 3 |
| Average week | -0.01% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.6% | +17 |
| AAVE perp | +23.8% | +5 |
| LTC perp | +21.8% | +9 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -41.5% | -18 |
| BTC perp | -34.4% | -5 |
| DOGE perp | -33.9% | -9 |
| DOT perp | -20.9% | -25 |
| BNB perp | -19.8% | -3 |
| ADA perp | -19.8% | -10 |
| ZEC perp | -16.0% | -3 |
| LINK perp | -14.1% | -3 |
| NEAR perp | -8.9% | -1 |
| XLM perp | -8.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
