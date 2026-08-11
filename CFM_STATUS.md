# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9311** (-6.89% since start) |
| Peak / drawdown | 1.0141 / -8.19% |
| Ticks recorded | 444 |
| Last tick | 2026-08-11T16:15:58.759177+00:00 (-0.6075%) |
| Risk rails | normal (dd -8.2%) |
| Data source | coinbase-cfm (bar 2026-08-11 15:00:00+00:00) |
| Gross leverage | 2.95x |
| Weeks tracked | 3 |
| Average week | +0.25% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.0% | +17 |
| AAVE perp | +23.2% | +5 |
| XLM perp | +17.2% | +2 |
| LTC perp | +16.9% | +7 |
| BTC perp | +13.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -39.2% | -6 |
| DOGE perp | -38.0% | -10 |
| BCH perp | -36.4% | -16 |
| ZEC perp | -30.3% | -6 |
| NEAR perp | -16.7% | -2 |
| ADA perp | -15.9% | -8 |
| DOT perp | -5.0% | -6 |
| LINK perp | -4.6% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
