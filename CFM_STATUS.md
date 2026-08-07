# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9353** (-6.47% since start) |
| Peak / drawdown | 1.0141 / -7.77% |
| Ticks recorded | 343 |
| Last tick | 2026-08-07T10:09:28.469604+00:00 (-0.1361%) |
| Risk rails | normal (dd -7.8%) |
| Data source | coinbase-cfm (bar 2026-08-07 09:00:00+00:00) |
| Gross leverage | 2.66x |
| Weeks tracked | 2 |
| Average week | +0.60% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.54% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.6% | +14 |
| ADA perp | +21.6% | +10 |
| XLM perp | +17.3% | +2 |
| SOL perp | +7.9% | +2 |
| XRP perp | +5.5% | +1 |
| AAVE perp | +4.8% | +1 |
| LTC perp | +2.4% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -46.2% | -20 |
| BNB perp | -37.8% | -6 |
| DOGE perp | -37.2% | -10 |
| ZEC perp | -16.4% | -3 |
| LINK perp | -13.2% | -3 |
| DOT perp | -13.1% | -15 |
| NEAR perp | -8.8% | -1 |
| AVAX perp | -4.8% | -7 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
