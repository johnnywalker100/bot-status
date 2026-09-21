# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9255** (-7.45% since start) |
| Peak / drawdown | 1.0141 / -8.74% |
| Ticks recorded | 1405 |
| Last tick | 2026-09-21T00:08:21.548070+00:00 (+0.7058%) |
| Risk rails | normal (dd -8.7%) |
| Data source | coinbase-cfm (bar 2026-09-20 23:00:00+00:00) |
| Gross leverage | 0.80x |
| Weeks tracked | 9 |
| Average week | +0.05% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.4% | +1 |
| SOL perp | +12.1% | +2 |
| XLM perp | +10.8% | +1 |
| DOT perp | +9.9% | +8 |
| BCH perp | +8.3% | +3 |
| LINK perp | +6.8% | +1 |
| AVAX perp | +5.0% | +4 |
| LTC perp | +3.2% | +1 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
