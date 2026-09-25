# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9599** (-4.01% since start) |
| Peak / drawdown | 1.0141 / -5.35% |
| Ticks recorded | 1512 |
| Last tick | 2026-09-25T11:08:21.111669+00:00 (+0.9217%) |
| Risk rails | normal (dd -5.3%) |
| Data source | coinbase-cfm (bar 2026-09-25 10:00:00+00:00) |
| Gross leverage | 0.93x |
| Weeks tracked | 9 |
| Average week | +0.46% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.7% | +1 |
| XLM perp | +11.6% | +1 |
| DOT perp | +11.0% | +9 |
| AVAX perp | +7.7% | +7 |
| AAVE perp | +7.7% | +1 |
| LINK perp | +7.3% | +1 |
| BCH perp | +7.1% | +2 |
| SOL perp | +6.3% | +1 |
| ETH perp | +5.7% | +2 |
| LTC perp | +3.7% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
