# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8806** (-11.94% since start) |
| Peak / drawdown | 1.0141 / -13.16% |
| Ticks recorded | 898 |
| Last tick | 2026-08-30T17:08:25.982639+00:00 (+0.0657%) |
| Risk rails | brake: drawdown -13.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-30 16:00:00+00:00) |
| Gross leverage | 0.07x |
| Weeks tracked | 5 |
| Average week | -0.95% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.73% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +2.9% | +1 |
| AVAX perp | +2.5% | +3 |
| DOT perp | +2.0% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
