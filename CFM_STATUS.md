# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9291** (-7.09% since start) |
| Peak / drawdown | 1.0141 / -8.38% |
| Ticks recorded | 349 |
| Last tick | 2026-08-07T16:08:44.515174+00:00 (-0.2133%) |
| Risk rails | normal (dd -8.4%) |
| Data source | coinbase-cfm (bar 2026-08-07 15:00:00+00:00) |
| Gross leverage | 2.67x |
| Weeks tracked | 2 |
| Average week | +0.27% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.20% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.9% | +14 |
| ADA perp | +21.6% | +10 |
| XLM perp | +17.3% | +2 |
| SOL perp | +8.0% | +2 |
| XRP perp | +5.5% | +1 |
| AAVE perp | +4.8% | +1 |
| LTC perp | +2.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -46.5% | -20 |
| BNB perp | -38.3% | -6 |
| DOGE perp | -37.7% | -10 |
| ZEC perp | -16.6% | -3 |
| LINK perp | -13.4% | -3 |
| DOT perp | -12.2% | -14 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -4.8% | -7 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
