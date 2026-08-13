# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9295** (-7.05% since start) |
| Peak / drawdown | 1.0141 / -8.34% |
| Ticks recorded | 495 |
| Last tick | 2026-08-13T19:08:46.353398+00:00 (-0.2138%) |
| Risk rails | normal (dd -8.3%) |
| Data source | coinbase-cfm (bar 2026-08-13 18:00:00+00:00) |
| Gross leverage | 3.12x |
| Weeks tracked | 3 |
| Average week | +0.19% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.5% | +14 |
| AAVE perp | +23.6% | +5 |
| LTC perp | +21.6% | +9 |
| XLM perp | +17.2% | +2 |
| SOL perp | +16.4% | +4 |
| AVAX perp | +6.9% | +10 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -37.7% | -10 |
| BCH perp | -31.0% | -14 |
| LINK perp | -23.7% | -5 |
| BTC perp | -20.5% | -3 |
| BNB perp | -19.7% | -3 |
| NEAR perp | -17.6% | -2 |
| DOT perp | -17.5% | -21 |
| ADA perp | -13.7% | -7 |
| XRP perp | -10.9% | -2 |
| ZEC perp | -5.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
