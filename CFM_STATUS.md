# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9181** (-8.19% since start) |
| Peak / drawdown | 1.0141 / -9.47% |
| Ticks recorded | 309 |
| Last tick | 2026-08-06T00:11:04.939927+00:00 (-0.1980%) |
| Risk rails | normal (dd -9.5%) |
| Data source | coinbase-cfm (bar 2026-08-05 23:00:00+00:00) |
| Gross leverage | 3.09x |
| Weeks tracked | 2 |
| Average week | -0.32% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.37% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.3% | +16 |
| XLM perp | +26.8% | +3 |
| AAVE perp | +19.5% | +4 |
| SOL perp | +16.1% | +4 |
| ADA perp | +14.6% | +7 |
| BTC perp | +7.0% | +1 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.3% | -9 |
| BCH perp | -23.2% | -10 |
| XRP perp | -23.1% | -4 |
| ZEC perp | -22.3% | -4 |
| LTC perp | -22.2% | -9 |
| BNB perp | -19.4% | -3 |
| LINK perp | -17.8% | -4 |
| DOT perp | -14.7% | -16 |
| NEAR perp | -9.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
