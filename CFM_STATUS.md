# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9331** (-6.69% since start) |
| Peak / drawdown | 1.0141 / -7.99% |
| Ticks recorded | 163 |
| Last tick | 2026-07-30T21:09:12.448543+00:00 (-0.1306%) |
| Risk rails | normal (dd -8.0%) |
| Data source | coinbase-cfm (bar 2026-07-30 20:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +0.95% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.95% / +0.95% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.9% | +12 |
| AAVE perp | +21.2% | +4 |
| ETH perp | +16.5% | +8 |
| DOT perp | +13.2% | +16 |
| XLM perp | +9.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.4% | -12 |
| LTC perp | -39.2% | -16 |
| NEAR perp | -27.1% | -3 |
| BNB perp | -25.4% | -4 |
| ZEC perp | -25.3% | -5 |
| LINK perp | -18.1% | -4 |
| BTC perp | -13.9% | -2 |
| AVAX perp | -9.0% | -13 |
| BCH perp | -7.0% | -3 |
| XRP perp | -5.8% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
