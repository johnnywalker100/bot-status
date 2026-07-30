# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9379** (-6.21% since start) |
| Peak / drawdown | 1.0141 / -7.52% |
| Ticks recorded | 154 |
| Last tick | 2026-07-30T12:08:31.803889+00:00 (-0.3379%) |
| Risk rails | normal (dd -7.5%) |
| Data source | coinbase-cfm (bar 2026-07-30 11:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +1.46% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.46% / +1.46% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.9% | +13 |
| AAVE perp | +21.1% | +4 |
| ETH perp | +16.4% | +8 |
| DOT perp | +13.9% | +17 |
| XLM perp | +9.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.9% | -12 |
| LTC perp | -38.7% | -16 |
| NEAR perp | -26.5% | -3 |
| ZEC perp | -25.5% | -5 |
| BNB perp | -25.0% | -4 |
| LINK perp | -18.0% | -4 |
| BTC perp | -13.8% | -2 |
| BCH perp | -9.0% | -4 |
| AVAX perp | -7.6% | -11 |
| XRP perp | -5.8% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
