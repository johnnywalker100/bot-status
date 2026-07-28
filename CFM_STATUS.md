# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9418** (-5.82% since start) |
| Peak / drawdown | 1.0141 / -7.13% |
| Ticks recorded | 96 |
| Last tick | 2026-07-28T03:08:42.031070+00:00 (+0.0059%) |
| Risk rails | normal (dd -7.1%) |
| Data source | coinbase-cfm (bar 2026-07-28 02:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 1 |
| Average week | +1.89% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.89% / +1.89% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +25.8% | +5 |
| ADA perp | +24.7% | +15 |
| BCH perp | +13.6% | +6 |
| ETH perp | +9.9% | +5 |
| DOT perp | +8.9% | +11 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.3% | -13 |
| LTC perp | -34.4% | -14 |
| LINK perp | -26.5% | -6 |
| BNB perp | -24.0% | -4 |
| BTC perp | -20.1% | -3 |
| NEAR perp | -17.8% | -2 |
| ZEC perp | -15.1% | -3 |
| AVAX perp | -12.9% | -19 |
| XLM perp | -9.1% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
