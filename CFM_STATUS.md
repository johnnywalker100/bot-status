# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8711** (-12.89% since start) |
| Peak / drawdown | 1.0141 / -14.10% |
| Ticks recorded | 1271 |
| Last tick | 2026-09-15T08:08:12.648054+00:00 (-0.0854%) |
| Risk rails | brake: drawdown -14.1% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-15 07:00:00+00:00) |
| Gross leverage | 0.32x |
| Weeks tracked | 8 |
| Average week | -0.73% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.2% | +1 |
| AVAX perp | +6.0% | +7 |
| SOL perp | +5.8% | +1 |
| DOT perp | +3.4% | +3 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.7% | -1 |
| BCH perp | -2.5% | -1 |
| ADA perp | -2.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
