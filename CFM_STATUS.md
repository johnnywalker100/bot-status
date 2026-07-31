# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9365** (-6.35% since start) |
| Peak / drawdown | 1.0141 / -7.66% |
| Ticks recorded | 166 |
| Last tick | 2026-07-31T00:08:53.310281+00:00 (+0.3164%) |
| Risk rails | normal (dd -7.7%) |
| Data source | coinbase-cfm (bar 2026-07-30 23:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 1 |
| Average week | +1.31% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.31% / +1.31% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.8% | +12 |
| AAVE perp | +21.2% | +4 |
| ETH perp | +16.4% | +8 |
| DOT perp | +13.1% | +16 |
| XLM perp | +9.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.2% | -12 |
| LTC perp | -38.9% | -16 |
| NEAR perp | -26.9% | -3 |
| BNB perp | -25.3% | -4 |
| ZEC perp | -25.1% | -5 |
| LINK perp | -18.0% | -4 |
| BTC perp | -13.8% | -2 |
| AVAX perp | -8.9% | -13 |
| BCH perp | -7.0% | -3 |
| XRP perp | -5.8% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
