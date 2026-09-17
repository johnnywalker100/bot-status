# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8722** (-12.78% since start) |
| Peak / drawdown | 1.0141 / -14.00% |
| Ticks recorded | 1311 |
| Last tick | 2026-09-17T00:08:39.922215+00:00 (+0.4544%) |
| Risk rails | brake: drawdown -14.0% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-16 23:00:00+00:00) |
| Gross leverage | 0.38x |
| Weeks tracked | 8 |
| Average week | -0.71% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +6.9% | +1 |
| LINK perp | +6.3% | +1 |
| SOL perp | +5.7% | +1 |
| DOT perp | +4.7% | +4 |
| AVAX perp | +4.3% | +5 |
| ETH perp | +2.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.6% | -1 |
| ADA perp | -2.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
