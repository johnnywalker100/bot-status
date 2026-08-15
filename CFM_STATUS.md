# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9120** (-8.80% since start) |
| Peak / drawdown | 1.0141 / -10.07% |
| Ticks recorded | 533 |
| Last tick | 2026-08-15T10:08:50.409797+00:00 (-0.5214%) |
| Risk rails | normal (dd -10.1%) |
| Data source | coinbase-cfm (bar 2026-08-15 09:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 3 |
| Average week | -0.43% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.80% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +28.6% | +6 |
| XLM perp | +17.4% | +2 |
| AVAX perp | +7.9% | +11 |
| BCH perp | +6.7% | +3 |
| ETH perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.4% | -10 |
| NEAR perp | -35.9% | -4 |
| BTC perp | -34.5% | -5 |
| LTC perp | -33.8% | -14 |
| BNB perp | -26.8% | -4 |
| LINK perp | -25.6% | -5 |
| ZEC perp | -10.7% | -2 |
| ADA perp | -9.8% | -5 |
| DOT perp | -8.5% | -10 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
