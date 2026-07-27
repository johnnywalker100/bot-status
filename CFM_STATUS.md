# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9245** (-7.55% since start) |
| Peak / drawdown | 1.0141 / -8.84% |
| Ticks recorded | 80 |
| Last tick | 2026-07-27T11:08:39.897881+00:00 (+0.1521%) |
| Risk rails | normal (dd -8.8%) |
| Data source | coinbase-cfm (bar 2026-07-27 10:00:00+00:00) |
| Gross leverage | 2.87x |
| Weeks tracked | 1 |
| Average week | +0.01% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.01% / +0.01% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +27.3% | +5 |
| ADA perp | +25.0% | +14 |
| XLM perp | +19.7% | +2 |
| BCH perp | +18.9% | +8 |
| ETH perp | +10.6% | +5 |
| DOT perp | +1.8% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.1% | -13 |
| LTC perp | -35.6% | -14 |
| BTC perp | -21.2% | -3 |
| LINK perp | -19.0% | -4 |
| BNB perp | -18.6% | -3 |
| ZEC perp | -16.3% | -3 |
| XRP perp | -12.0% | -2 |
| NEAR perp | -9.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
