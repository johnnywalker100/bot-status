# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9239** (-7.61% since start) |
| Peak / drawdown | 1.0141 / -8.90% |
| Ticks recorded | 375 |
| Last tick | 2026-08-08T19:09:19.150911+00:00 (+0.2715%) |
| Risk rails | normal (dd -8.9%) |
| Data source | coinbase-cfm (bar 2026-08-08 18:00:00+00:00) |
| Gross leverage | 2.72x |
| Weeks tracked | 2 |
| Average week | -0.01% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.76% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.2% | +15 |
| AAVE perp | +24.7% | +5 |
| ADA perp | +13.0% | +6 |
| XLM perp | +8.9% | +1 |
| SOL perp | +8.2% | +2 |
| LTC perp | +7.4% | +3 |
| XRP perp | +5.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -46.0% | -12 |
| BNB perp | -39.2% | -6 |
| BCH perp | -32.9% | -14 |
| ZEC perp | -16.4% | -3 |
| DOT perp | -14.2% | -16 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.8% | -1 |
| AVAX perp | -6.4% | -9 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
