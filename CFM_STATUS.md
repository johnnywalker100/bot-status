# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9562** (-4.38% since start) |
| Peak / drawdown | 1.0141 / -5.71% |
| Ticks recorded | 1584 |
| Last tick | 2026-09-28T12:08:23.939313+00:00 (+0.7186%) |
| Risk rails | normal (dd -5.7%) |
| Data source | coinbase-cfm (bar 2026-09-28 11:00:00+00:00) |
| Gross leverage | 0.88x |
| Weeks tracked | 10 |
| Average week | +0.38% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.7% | +1 |
| DOT perp | +11.4% | +9 |
| ETH perp | +11.2% | +4 |
| BTC perp | +8.7% | +1 |
| AAVE perp | +7.8% | +1 |
| AVAX perp | +7.8% | +7 |
| BCH perp | +6.6% | +2 |
| SOL perp | +6.3% | +1 |
| LTC perp | +3.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.9% | -1 |
| ADA perp | -2.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
