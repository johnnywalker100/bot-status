# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9193** (-8.07% since start) |
| Peak / drawdown | 1.0141 / -9.35% |
| Ticks recorded | 83 |
| Last tick | 2026-07-27T14:08:40.536210+00:00 (-0.2344%) |
| Risk rails | normal (dd -9.3%) |
| Data source | coinbase-cfm (bar 2026-07-27 13:00:00+00:00) |
| Gross leverage | 2.88x |
| Weeks tracked | 1 |
| Average week | -0.54% |
| Weeks >= +3% | 0% |
| Best / worst week | -0.54% / -0.54% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +27.2% | +5 |
| ADA perp | +25.0% | +14 |
| XLM perp | +19.6% | +2 |
| BCH perp | +19.0% | +8 |
| ETH perp | +10.7% | +5 |
| DOT perp | +1.8% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.4% | -13 |
| LTC perp | -35.9% | -14 |
| BTC perp | -21.3% | -3 |
| LINK perp | -19.0% | -4 |
| BNB perp | -18.7% | -3 |
| ZEC perp | -16.3% | -3 |
| XRP perp | -12.0% | -2 |
| NEAR perp | -9.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
