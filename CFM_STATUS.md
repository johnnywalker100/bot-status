# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9548** (-4.52% since start) |
| Peak / drawdown | 1.0141 / -5.85% |
| Ticks recorded | 108 |
| Last tick | 2026-07-28T15:09:08.889324+00:00 (-0.1788%) |
| Risk rails | normal (dd -5.8%) |
| Data source | coinbase-cfm (bar 2026-07-28 14:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 1 |
| Average week | +3.29% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.29% / +3.29% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +31.1% | +6 |
| ADA perp | +22.9% | +14 |
| BCH perp | +13.3% | +6 |
| ETH perp | +9.9% | +5 |
| DOT perp | +6.3% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.2% | -14 |
| LTC perp | -33.8% | -14 |
| LINK perp | -26.0% | -6 |
| BNB perp | -23.8% | -4 |
| BTC perp | -19.9% | -3 |
| NEAR perp | -17.1% | -2 |
| ZEC perp | -14.7% | -3 |
| AVAX perp | -14.2% | -21 |
| XLM perp | -8.9% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
