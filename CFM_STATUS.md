# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9316** (-6.84% since start) |
| Peak / drawdown | 1.0141 / -8.14% |
| Ticks recorded | 164 |
| Last tick | 2026-07-30T22:08:35.596924+00:00 (-0.1637%) |
| Risk rails | normal (dd -8.1%) |
| Data source | coinbase-cfm (bar 2026-07-30 21:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 1 |
| Average week | +0.78% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.78% / +0.78% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.9% | +12 |
| AAVE perp | +21.2% | +4 |
| ETH perp | +16.5% | +8 |
| DOT perp | +13.3% | +16 |
| XLM perp | +9.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.5% | -12 |
| LTC perp | -39.3% | -16 |
| NEAR perp | -27.2% | -3 |
| BNB perp | -25.4% | -4 |
| ZEC perp | -25.4% | -5 |
| LINK perp | -18.2% | -4 |
| BTC perp | -13.9% | -2 |
| AVAX perp | -9.0% | -13 |
| BCH perp | -7.0% | -3 |
| XRP perp | -5.8% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
