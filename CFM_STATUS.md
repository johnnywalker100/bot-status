# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8836** (-11.64% since start) |
| Peak / drawdown | 1.0141 / -12.86% |
| Ticks recorded | 1339 |
| Last tick | 2026-09-18T04:08:29.856546+00:00 (+0.3201%) |
| Risk rails | brake: drawdown -12.9% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-18 03:00:00+00:00) |
| Gross leverage | 0.28x |
| Weeks tracked | 8 |
| Average week | -0.55% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.75% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| LINK perp | +6.7% | +1 |
| SOL perp | +5.9% | +1 |
| DOT perp | +5.1% | +4 |
| AVAX perp | +4.5% | +5 |
| ETH perp | +2.8% | +1 |
| BCH perp | +2.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
