# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9060** (-9.40% since start) |
| Peak / drawdown | 1.0141 / -10.66% |
| Ticks recorded | 1362 |
| Last tick | 2026-09-19T04:08:24.258961+00:00 (-0.5515%) |
| Risk rails | normal (dd -10.7%) |
| Data source | coinbase-cfm (bar 2026-09-19 03:00:00+00:00) |
| Gross leverage | 0.80x |
| Weeks tracked | 8 |
| Average week | -0.22% |
| Weeks >= +3% | 12% |
| Best / worst week | +4.33% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +17.0% | +1 |
| SOL perp | +12.5% | +2 |
| XLM perp | +10.8% | +1 |
| DOT perp | +8.8% | +7 |
| AVAX perp | +7.5% | +8 |
| LINK perp | +6.9% | +1 |
| BCH perp | +5.5% | +2 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.9% | -1 |
| LTC perp | -3.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
