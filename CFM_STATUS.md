# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9200** (-8.00% since start) |
| Peak / drawdown | 1.0141 / -9.29% |
| Ticks recorded | 1403 |
| Last tick | 2026-09-20T22:08:14.173844+00:00 (+0.5991%) |
| Risk rails | normal (dd -9.3%) |
| Data source | coinbase-cfm (bar 2026-09-20 21:00:00+00:00) |
| Gross leverage | 0.80x |
| Weeks tracked | 8 |
| Average week | -0.02% |
| Weeks >= +3% | 12% |
| Best / worst week | +5.93% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.4% | +1 |
| SOL perp | +12.0% | +2 |
| XLM perp | +10.7% | +1 |
| DOT perp | +10.0% | +8 |
| BCH perp | +8.2% | +3 |
| LINK perp | +6.8% | +1 |
| AVAX perp | +5.0% | +4 |
| LTC perp | +3.2% | +1 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
