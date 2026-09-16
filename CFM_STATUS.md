# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8658** (-13.42% since start) |
| Peak / drawdown | 1.0141 / -14.62% |
| Ticks recorded | 1289 |
| Last tick | 2026-09-16T02:08:24.148200+00:00 (-0.1088%) |
| Risk rails | brake: drawdown -14.6% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-16 01:00:00+00:00) |
| Gross leverage | 0.38x |
| Weeks tracked | 8 |
| Average week | -0.80% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.0% | +1 |
| LINK perp | +6.2% | +1 |
| SOL perp | +5.6% | +1 |
| DOT perp | +5.4% | +5 |
| AVAX perp | +4.2% | +5 |
| ETH perp | +2.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.6% | -1 |
| ADA perp | -2.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
