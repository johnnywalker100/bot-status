# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8892** (-11.08% since start) |
| Peak / drawdown | 1.0141 / -12.32% |
| Ticks recorded | 723 |
| Last tick | 2026-08-23T09:08:24.993829+00:00 (+0.2269%) |
| Risk rails | brake: drawdown -12.3% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-23 08:00:00+00:00) |
| Gross leverage | 0.25x |
| Weeks tracked | 4 |
| Average week | -0.95% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.85% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.0% | +1 |
| SOL perp | +5.2% | +1 |
| BCH perp | +3.1% | +1 |
| DOT perp | +3.0% | +3 |
| ETH perp | +2.7% | +1 |
| ADA perp | +2.5% | +1 |
| AVAX perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
