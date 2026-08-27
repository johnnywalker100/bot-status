# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8801** (-11.99% since start) |
| Peak / drawdown | 1.0141 / -13.22% |
| Ticks recorded | 816 |
| Last tick | 2026-08-27T06:08:24.781409+00:00 (+0.0883%) |
| Risk rails | brake: drawdown -13.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-27 05:00:00+00:00) |
| Gross leverage | 0.19x |
| Weeks tracked | 5 |
| Average week | -0.97% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.79% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +5.8% | +1 |
| BCH perp | +3.0% | +1 |
| DOT perp | +3.0% | +3 |
| ETH perp | +2.8% | +1 |
| ADA perp | +2.4% | +1 |
| AVAX perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
