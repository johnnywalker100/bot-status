# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9368** (-6.32% since start) |
| Peak / drawdown | 1.0141 / -7.63% |
| Ticks recorded | 443 |
| Last tick | 2026-08-11T15:08:26.705451+00:00 (+1.3143%) |
| Risk rails | normal (dd -7.6%) |
| Data source | coinbase-cfm (bar 2026-08-11 14:00:00+00:00) |
| Gross leverage | 2.84x |
| Weeks tracked | 3 |
| Average week | +0.45% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.0% | +16 |
| AAVE perp | +23.4% | +5 |
| XLM perp | +17.0% | +2 |
| LTC perp | +16.8% | +7 |
| BTC perp | +6.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -38.9% | -6 |
| DOGE perp | -37.5% | -10 |
| BCH perp | -36.3% | -16 |
| ZEC perp | -30.4% | -6 |
| NEAR perp | -16.5% | -2 |
| ADA perp | -15.8% | -8 |
| LINK perp | -4.6% | -1 |
| DOT perp | -4.2% | -5 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
