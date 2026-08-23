# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8914** (-10.86% since start) |
| Peak / drawdown | 1.0141 / -12.10% |
| Ticks recorded | 725 |
| Last tick | 2026-08-23T11:08:11.861874+00:00 (+0.0915%) |
| Risk rails | brake: drawdown -12.1% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-23 10:00:00+00:00) |
| Gross leverage | 0.25x |
| Weeks tracked | 4 |
| Average week | -0.89% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.61% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.1% | +1 |
| SOL perp | +5.3% | +1 |
| DOT perp | +3.1% | +3 |
| BCH perp | +3.1% | +1 |
| ETH perp | +2.7% | +1 |
| ADA perp | +2.5% | +1 |
| AVAX perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
