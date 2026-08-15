# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9161** (-8.39% since start) |
| Peak / drawdown | 1.0141 / -9.67% |
| Ticks recorded | 524 |
| Last tick | 2026-08-15T01:13:13.852077+00:00 (-0.5240%) |
| Risk rails | normal (dd -9.6%) |
| Data source | coinbase-cfm (bar 2026-08-15 00:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 3 |
| Average week | -0.29% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.36% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +28.3% | +6 |
| XLM perp | +25.8% | +3 |
| BCH perp | +6.7% | +3 |
| AVAX perp | +6.4% | +9 |
| ETH perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.2% | -10 |
| NEAR perp | -36.0% | -4 |
| LTC perp | -35.7% | -15 |
| BTC perp | -34.3% | -5 |
| BNB perp | -26.5% | -4 |
| LINK perp | -24.9% | -5 |
| ZEC perp | -10.7% | -2 |
| ADA perp | -9.8% | -5 |
| DOT perp | -8.3% | -10 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
