# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9345** (-6.55% since start) |
| Peak / drawdown | 1.0141 / -7.85% |
| Ticks recorded | 474 |
| Last tick | 2026-08-12T22:08:17.784812+00:00 (+1.3429%) |
| Risk rails | normal (dd -7.8%) |
| Data source | coinbase-cfm (bar 2026-08-12 21:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 3 |
| Average week | +0.37% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.2% | +17 |
| AAVE perp | +23.5% | +5 |
| LTC perp | +21.6% | +9 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -40.7% | -18 |
| DOGE perp | -37.0% | -10 |
| BTC perp | -33.9% | -5 |
| DOT perp | -20.6% | -25 |
| BNB perp | -19.6% | -3 |
| ADA perp | -19.5% | -10 |
| ZEC perp | -15.7% | -3 |
| LINK perp | -13.9% | -3 |
| NEAR perp | -8.7% | -1 |
| XLM perp | -8.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
