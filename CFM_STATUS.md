# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9478** (-5.22% since start) |
| Peak / drawdown | 1.0141 / -6.54% |
| Ticks recorded | 117 |
| Last tick | 2026-07-29T00:08:47.571163+00:00 (-1.2206%) |
| Risk rails | normal (dd -6.5%) |
| Data source | coinbase-cfm (bar 2026-07-28 23:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 1 |
| Average week | +2.53% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.53% / +2.53% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.7% | +5 |
| ADA perp | +24.0% | +14 |
| BCH perp | +13.6% | +6 |
| ETH perp | +10.2% | +5 |
| DOT perp | +7.2% | +9 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.7% | -13 |
| LTC perp | -34.1% | -14 |
| LINK perp | -26.8% | -6 |
| BNB perp | -24.1% | -4 |
| BTC perp | -20.3% | -3 |
| NEAR perp | -17.5% | -2 |
| ZEC perp | -14.8% | -3 |
| AVAX perp | -13.2% | -19 |
| XLM perp | -9.2% | -1 |
| XRP perp | -5.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
