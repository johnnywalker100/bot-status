# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9332** (-6.68% since start) |
| Peak / drawdown | 1.0141 / -7.98% |
| Ticks recorded | 510 |
| Last tick | 2026-08-14T10:12:03.454685+00:00 (-0.0179%) |
| Risk rails | normal (dd -8.0%) |
| Data source | coinbase-cfm (bar 2026-08-14 09:00:00+00:00) |
| Gross leverage | 3.05x |
| Weeks tracked | 3 |
| Average week | +0.33% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.6% | +3 |
| AAVE perp | +23.2% | +5 |
| AVAX perp | +10.2% | +15 |
| ETH perp | +10.0% | +5 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -33.6% | -5 |
| DOGE perp | -33.5% | -9 |
| BNB perp | -32.6% | -5 |
| NEAR perp | -25.8% | -3 |
| LINK perp | -23.6% | -5 |
| BCH perp | -22.0% | -10 |
| ADA perp | -17.6% | -9 |
| ZEC perp | -15.7% | -3 |
| LTC perp | -14.3% | -6 |
| DOT perp | -8.1% | -10 |
| XRP perp | -5.4% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
