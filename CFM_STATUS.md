# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8923** (-10.77% since start) |
| Peak / drawdown | 1.0141 / -12.01% |
| Ticks recorded | 1388 |
| Last tick | 2026-09-20T07:08:17.862526+00:00 (+0.0690%) |
| Risk rails | brake: drawdown -12.0% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-20 06:00:00+00:00) |
| Gross leverage | 0.28x |
| Weeks tracked | 8 |
| Average week | -0.42% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.75% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +6.1% | +1 |
| DOT perp | +4.9% | +4 |
| AVAX perp | +3.3% | +3 |
| LTC perp | +3.2% | +1 |
| ETH perp | +2.9% | +1 |
| BCH perp | +2.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
