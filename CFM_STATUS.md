# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9087** (-9.13% since start) |
| Peak / drawdown | 1.0141 / -10.39% |
| Ticks recorded | 538 |
| Last tick | 2026-08-15T15:09:07.364478+00:00 (+0.0794%) |
| Risk rails | normal (dd -10.4%) |
| Data source | coinbase-cfm (bar 2026-08-15 14:00:00+00:00) |
| Gross leverage | 2.91x |
| Weeks tracked | 3 |
| Average week | -0.55% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.16% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +28.6% | +6 |
| XLM perp | +17.4% | +2 |
| AVAX perp | +7.9% | +11 |
| BCH perp | +6.8% | +3 |
| ETH perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.5% | -10 |
| NEAR perp | -36.0% | -4 |
| BTC perp | -34.6% | -5 |
| LTC perp | -33.9% | -14 |
| BNB perp | -26.9% | -4 |
| LINK perp | -20.8% | -4 |
| ZEC perp | -10.8% | -2 |
| ADA perp | -9.8% | -5 |
| DOT perp | -7.7% | -9 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
