# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9300** (-7.00% since start) |
| Peak / drawdown | 1.0141 / -8.29% |
| Ticks recorded | 446 |
| Last tick | 2026-08-11T18:09:39.731225+00:00 (-0.5740%) |
| Risk rails | normal (dd -8.3%) |
| Data source | coinbase-cfm (bar 2026-08-11 17:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 3 |
| Average week | +0.21% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.0% | +17 |
| AAVE perp | +23.4% | +5 |
| XLM perp | +17.3% | +2 |
| LTC perp | +17.0% | +7 |
| BTC perp | +13.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -39.3% | -6 |
| DOGE perp | -38.1% | -10 |
| BCH perp | -36.4% | -16 |
| ZEC perp | -30.4% | -6 |
| NEAR perp | -16.8% | -2 |
| ADA perp | -15.9% | -8 |
| DOT perp | -5.0% | -6 |
| LINK perp | -4.6% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
