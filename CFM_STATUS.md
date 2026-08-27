# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8837** (-11.63% since start) |
| Peak / drawdown | 1.0141 / -12.86% |
| Ticks recorded | 827 |
| Last tick | 2026-08-27T17:08:23.633407+00:00 (+0.0334%) |
| Risk rails | brake: drawdown -12.9% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-27 16:00:00+00:00) |
| Gross leverage | 0.10x |
| Weeks tracked | 5 |
| Average week | -0.89% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.40% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BCH perp | +3.1% | +1 |
| ETH perp | +2.9% | +1 |
| DOT perp | +2.0% | +2 |
| AVAX perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
