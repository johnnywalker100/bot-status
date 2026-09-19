# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9129** (-8.71% since start) |
| Peak / drawdown | 1.0141 / -9.98% |
| Ticks recorded | 1372 |
| Last tick | 2026-09-19T14:08:27.240920+00:00 (+0.0843%) |
| Risk rails | normal (dd -10.0%) |
| Data source | coinbase-cfm (bar 2026-09-19 13:00:00+00:00) |
| Gross leverage | 0.80x |
| Weeks tracked | 8 |
| Average week | -0.13% |
| Weeks >= +3% | 12% |
| Best / worst week | +5.11% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.8% | +1 |
| SOL perp | +12.2% | +2 |
| XLM perp | +11.0% | +1 |
| DOT perp | +8.7% | +7 |
| AVAX perp | +8.2% | +8 |
| LINK perp | +6.9% | +1 |
| BCH perp | +5.5% | +2 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.9% | -1 |
| LTC perp | -3.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
