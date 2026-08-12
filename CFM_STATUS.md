# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9205** (-7.95% since start) |
| Peak / drawdown | 1.0141 / -9.23% |
| Ticks recorded | 471 |
| Last tick | 2026-08-12T19:08:26.295658+00:00 (+0.3431%) |
| Risk rails | normal (dd -9.2%) |
| Data source | coinbase-cfm (bar 2026-08-12 18:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 3 |
| Average week | -0.13% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.8% | +16 |
| AAVE perp | +24.1% | +5 |
| LTC perp | +22.0% | +9 |
| AVAX perp | +0.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -41.8% | -18 |
| DOGE perp | -38.3% | -10 |
| BTC perp | -34.4% | -5 |
| DOT perp | -20.3% | -24 |
| ADA perp | -19.9% | -10 |
| BNB perp | -19.9% | -3 |
| ZEC perp | -16.1% | -3 |
| LINK perp | -14.3% | -3 |
| NEAR perp | -8.9% | -1 |
| XLM perp | -8.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
