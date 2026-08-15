# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9103** (-8.97% since start) |
| Peak / drawdown | 1.0141 / -10.24% |
| Ticks recorded | 525 |
| Last tick | 2026-08-15T02:08:39.705975+00:00 (-0.6317%) |
| Risk rails | normal (dd -10.2%) |
| Data source | coinbase-cfm (bar 2026-08-15 01:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | -0.50% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.98% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +28.5% | +6 |
| XLM perp | +26.1% | +3 |
| BCH perp | +6.8% | +3 |
| AVAX perp | +6.4% | +9 |
| ETH perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.5% | -10 |
| NEAR perp | -36.0% | -4 |
| BTC perp | -34.6% | -5 |
| LTC perp | -33.7% | -14 |
| BNB perp | -26.7% | -4 |
| LINK perp | -20.7% | -4 |
| ZEC perp | -10.9% | -2 |
| ADA perp | -9.9% | -5 |
| DOT perp | -8.4% | -10 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
