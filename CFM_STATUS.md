# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9072** (-9.28% since start) |
| Peak / drawdown | 1.0141 / -10.54% |
| Ticks recorded | 527 |
| Last tick | 2026-08-15T04:08:57.447083+00:00 (+0.8620%) |
| Risk rails | normal (dd -10.5%) |
| Data source | coinbase-cfm (bar 2026-08-15 03:00:00+00:00) |
| Gross leverage | 2.93x |
| Weeks tracked | 3 |
| Average week | -0.61% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.32% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +28.7% | +6 |
| XLM perp | +17.5% | +2 |
| AVAX perp | +7.4% | +10 |
| BCH perp | +6.8% | +3 |
| ETH perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.7% | -10 |
| NEAR perp | -36.2% | -4 |
| BTC perp | -34.7% | -5 |
| LTC perp | -33.9% | -14 |
| BNB perp | -26.9% | -4 |
| LINK perp | -21.0% | -4 |
| ZEC perp | -10.9% | -2 |
| ADA perp | -10.0% | -5 |
| DOT perp | -8.5% | -10 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
