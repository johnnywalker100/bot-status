# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9595** (-4.05% since start) |
| Peak / drawdown | 1.0141 / -5.39% |
| Ticks recorded | 116 |
| Last tick | 2026-07-28T23:08:46.026540+00:00 (+1.5170%) |
| Risk rails | normal (dd -5.4%) |
| Data source | coinbase-cfm (bar 2026-07-28 22:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +3.80% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.80% / +3.80% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +31.1% | +6 |
| ADA perp | +23.5% | +14 |
| BCH perp | +13.3% | +6 |
| ETH perp | +9.9% | +5 |
| DOT perp | +7.1% | +9 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.1% | -14 |
| LTC perp | -33.5% | -14 |
| LINK perp | -26.1% | -6 |
| BNB perp | -23.7% | -4 |
| BTC perp | -19.9% | -3 |
| NEAR perp | -17.1% | -2 |
| ZEC perp | -14.4% | -3 |
| AVAX perp | -12.9% | -19 |
| XLM perp | -9.0% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
