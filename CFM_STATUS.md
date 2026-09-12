# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8709** (-12.91% since start) |
| Peak / drawdown | 1.0141 / -14.13% |
| Ticks recorded | 1207 |
| Last tick | 2026-09-12T16:08:43.124576+00:00 (-0.0245%) |
| Risk rails | brake: drawdown -14.1% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-12 15:00:00+00:00) |
| Gross leverage | 0.34x |
| Weeks tracked | 7 |
| Average week | -0.84% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BTC perp | +8.9% | +1 |
| AAVE perp | +7.2% | +1 |
| SOL perp | +5.9% | +1 |
| AVAX perp | +5.1% | +6 |
| ETH perp | +2.9% | +1 |
| DOT perp | +1.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| ADA perp | -2.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
