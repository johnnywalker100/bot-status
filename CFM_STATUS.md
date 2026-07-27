# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9244** (-7.56% since start) |
| Peak / drawdown | 1.0141 / -8.85% |
| Ticks recorded | 73 |
| Last tick | 2026-07-27T04:08:40.138233+00:00 (+0.0000%) |
| Risk rails | daily kill: flat until 2026-07-27T07:08Z |
| Data source | coinbase-cfm (bar 2026-07-27 03:00:00+00:00) |
| Gross leverage | 0.00x |
| Weeks tracked | 1 |
| Average week | +0.00% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.00% / +0.00% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| (none) | | |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
