# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9168** (-8.32% since start) |
| Peak / drawdown | 1.0141 / -9.59% |
| Ticks recorded | 532 |
| Last tick | 2026-08-15T09:08:38.640042+00:00 (+0.4084%) |
| Risk rails | normal (dd -9.6%) |
| Data source | coinbase-cfm (bar 2026-08-15 08:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 3 |
| Average week | -0.26% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.28% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +28.4% | +6 |
| XLM perp | +25.9% | +3 |
| AVAX perp | +7.9% | +11 |
| BCH perp | +6.7% | +3 |
| ETH perp | +2.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.1% | -10 |
| NEAR perp | -35.6% | -4 |
| BTC perp | -34.3% | -5 |
| LTC perp | -33.5% | -14 |
| BNB perp | -26.6% | -4 |
| LINK perp | -25.3% | -5 |
| ZEC perp | -10.6% | -2 |
| ADA perp | -9.7% | -5 |
| DOT perp | -8.4% | -10 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
