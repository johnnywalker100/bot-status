# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8669** (-13.31% since start) |
| Peak / drawdown | 1.0141 / -14.52% |
| Ticks recorded | 1285 |
| Last tick | 2026-09-15T22:08:41.247570+00:00 (-0.0826%) |
| Risk rails | brake: drawdown -14.5% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-15 21:00:00+00:00) |
| Gross leverage | 0.31x |
| Weeks tracked | 8 |
| Average week | -0.79% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.0% | +1 |
| AVAX perp | +5.8% | +7 |
| SOL perp | +5.6% | +1 |
| DOT perp | +3.3% | +3 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.6% | -1 |
| BCH perp | -2.5% | -1 |
| ADA perp | -2.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
