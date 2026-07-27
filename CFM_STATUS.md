# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9219** (-7.81% since start) |
| Peak / drawdown | 1.0141 / -9.09% |
| Ticks recorded | 77 |
| Last tick | 2026-07-27T08:08:41.728278+00:00 (-0.2611%) |
| Risk rails | normal (dd -8.9%) |
| Data source | coinbase-cfm (bar 2026-07-27 07:00:00+00:00) |
| Gross leverage | 2.86x |
| Weeks tracked | 1 |
| Average week | -0.26% |
| Weeks >= +3% | 0% |
| Best / worst week | -0.26% / -0.26% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +27.5% | +5 |
| ADA perp | +25.0% | +14 |
| XLM perp | +19.6% | +2 |
| BCH perp | +18.7% | +8 |
| ETH perp | +10.6% | +5 |
| DOT perp | +0.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.1% | -13 |
| LTC perp | -35.7% | -14 |
| BTC perp | -21.2% | -3 |
| LINK perp | -19.0% | -4 |
| BNB perp | -18.6% | -3 |
| ZEC perp | -16.2% | -3 |
| XRP perp | -12.0% | -2 |
| NEAR perp | -9.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
