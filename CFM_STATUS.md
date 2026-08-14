# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9278** (-7.22% since start) |
| Peak / drawdown | 1.0141 / -8.51% |
| Ticks recorded | 500 |
| Last tick | 2026-08-14T00:08:36.825891+00:00 (-0.0774%) |
| Risk rails | normal (dd -8.5%) |
| Data source | coinbase-cfm (bar 2026-08-13 23:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 3 |
| Average week | +0.13% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.4% | +14 |
| AAVE perp | +23.8% | +5 |
| LTC perp | +21.7% | +9 |
| SOL perp | +12.3% | +3 |
| XLM perp | +8.6% | +1 |
| AVAX perp | +7.0% | +10 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -37.8% | -10 |
| BCH perp | -31.1% | -14 |
| LINK perp | -23.9% | -5 |
| BTC perp | -20.5% | -3 |
| BNB perp | -19.7% | -3 |
| NEAR perp | -17.7% | -2 |
| DOT perp | -17.5% | -21 |
| ADA perp | -13.8% | -7 |
| XRP perp | -10.9% | -2 |
| ZEC perp | -5.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
