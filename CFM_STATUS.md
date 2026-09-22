# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9327** (-6.73% since start) |
| Peak / drawdown | 1.0141 / -8.02% |
| Ticks recorded | 1441 |
| Last tick | 2026-09-22T12:08:31.059138+00:00 (+0.5601%) |
| Risk rails | normal (dd -8.0%) |
| Data source | coinbase-cfm (bar 2026-09-22 11:00:00+00:00) |
| Gross leverage | 0.93x |
| Weeks tracked | 9 |
| Average week | +0.13% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.4% | +1 |
| SOL perp | +12.6% | +2 |
| XLM perp | +11.3% | +1 |
| DOT perp | +11.2% | +9 |
| AAVE perp | +7.6% | +1 |
| AVAX perp | +7.0% | +6 |
| LINK perp | +6.9% | +1 |
| ETH perp | +5.9% | +2 |
| LTC perp | +3.2% | +1 |
| BCH perp | +2.9% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
