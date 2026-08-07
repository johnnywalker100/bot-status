# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9311** (-6.89% since start) |
| Peak / drawdown | 1.0141 / -8.18% |
| Ticks recorded | 348 |
| Last tick | 2026-08-07T15:08:40.872580+00:00 (+0.1267%) |
| Risk rails | normal (dd -8.2%) |
| Data source | coinbase-cfm (bar 2026-08-07 14:00:00+00:00) |
| Gross leverage | 2.66x |
| Weeks tracked | 2 |
| Average week | +0.37% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.99% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.8% | +14 |
| ADA perp | +21.3% | +10 |
| XLM perp | +17.2% | +2 |
| SOL perp | +7.9% | +2 |
| XRP perp | +5.5% | +1 |
| AAVE perp | +4.8% | +1 |
| LTC perp | +2.4% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -46.2% | -20 |
| BNB perp | -38.1% | -6 |
| DOGE perp | -37.5% | -10 |
| ZEC perp | -16.4% | -3 |
| LINK perp | -13.3% | -3 |
| DOT perp | -13.0% | -15 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -4.8% | -7 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
