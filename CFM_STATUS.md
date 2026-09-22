# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9336** (-6.64% since start) |
| Peak / drawdown | 1.0141 / -7.94% |
| Ticks recorded | 1431 |
| Last tick | 2026-09-22T02:08:14.999901+00:00 (-0.2058%) |
| Risk rails | normal (dd -7.9%) |
| Data source | coinbase-cfm (bar 2026-09-22 01:00:00+00:00) |
| Gross leverage | 0.90x |
| Weeks tracked | 9 |
| Average week | +0.14% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +15.7% | +1 |
| SOL perp | +12.6% | +2 |
| DOT perp | +11.5% | +9 |
| XLM perp | +11.4% | +1 |
| AAVE perp | +7.7% | +1 |
| AVAX perp | +7.2% | +6 |
| LINK perp | +7.0% | +1 |
| LTC perp | +3.3% | +1 |
| ETH perp | +2.9% | +1 |
| BCH perp | +2.8% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
