# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9623** (-3.77% since start) |
| Peak / drawdown | 1.0141 / -5.11% |
| Ticks recorded | 1453 |
| Last tick | 2026-09-23T00:08:41.712054+00:00 (-0.3167%) |
| Risk rails | normal (dd -5.1%) |
| Data source | coinbase-cfm (bar 2026-09-22 23:00:00+00:00) |
| Gross leverage | 0.90x |
| Weeks tracked | 9 |
| Average week | +0.49% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.8% | +1 |
| SOL perp | +12.3% | +2 |
| DOT perp | +11.4% | +9 |
| XLM perp | +11.2% | +1 |
| AAVE perp | +7.7% | +1 |
| AVAX perp | +7.0% | +6 |
| LINK perp | +6.8% | +1 |
| ETH perp | +5.7% | +2 |
| LTC perp | +3.3% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
