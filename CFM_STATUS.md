# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9276** (-7.24% since start) |
| Peak / drawdown | 1.0141 / -8.53% |
| Ticks recorded | 448 |
| Last tick | 2026-08-11T20:08:26.071606+00:00 (-0.6074%) |
| Risk rails | normal (dd -8.5%) |
| Data source | coinbase-cfm (bar 2026-08-11 19:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 3 |
| Average week | +0.12% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.5% | +16 |
| AAVE perp | +23.8% | +5 |
| XLM perp | +17.5% | +2 |
| LTC perp | +17.2% | +7 |
| BTC perp | +13.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -39.6% | -6 |
| DOGE perp | -38.5% | -10 |
| BCH perp | -36.7% | -16 |
| ZEC perp | -30.8% | -6 |
| NEAR perp | -17.0% | -2 |
| ADA perp | -16.1% | -8 |
| DOT perp | -5.1% | -6 |
| LINK perp | -4.7% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
