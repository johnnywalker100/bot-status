# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9166** (-8.34% since start) |
| Peak / drawdown | 1.0141 / -9.61% |
| Ticks recorded | 490 |
| Last tick | 2026-08-13T14:09:27.865742+00:00 (-0.3070%) |
| Risk rails | normal (dd -9.6%) |
| Data source | coinbase-cfm (bar 2026-08-13 13:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | -0.27% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.30% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.8% | +14 |
| AAVE perp | +23.9% | +5 |
| LTC perp | +21.9% | +9 |
| SOL perp | +12.4% | +3 |
| XLM perp | +8.7% | +1 |
| AVAX perp | +6.4% | +9 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.2% | -10 |
| BCH perp | -32.6% | -14 |
| BTC perp | -20.8% | -3 |
| BNB perp | -20.0% | -3 |
| LINK perp | -19.2% | -4 |
| NEAR perp | -18.1% | -2 |
| DOT perp | -17.6% | -21 |
| ADA perp | -14.1% | -7 |
| XRP perp | -11.0% | -2 |
| ZEC perp | -5.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
