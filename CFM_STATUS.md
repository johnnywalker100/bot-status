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
| Ticks recorded | 66 |
| Last tick | 2026-07-26T21:08:39.364088+00:00 (+0.0000%) |
| Risk rails | daily kill switch active until 2026-07-27 07:08:41.918699+00:00 |
| Data source | coinbase-cfm (bar 2026-07-26 20:00:00+00:00) |
| Gross leverage | 0.00x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| (none) | | |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
