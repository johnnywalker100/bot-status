# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9511** (-4.89% since start) |
| Peak / drawdown | 1.0141 / -6.21% |
| Ticks recorded | 1518 |
| Last tick | 2026-09-25T17:08:42.454855+00:00 (+0.1627%) |
| Risk rails | normal (dd -6.2%) |
| Data source | coinbase-cfm (bar 2026-09-25 16:00:00+00:00) |
| Gross leverage | 0.95x |
| Weeks tracked | 9 |
| Average week | +0.36% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.3% | +1 |
| XLM perp | +11.4% | +1 |
| DOT perp | +11.2% | +9 |
| ETH perp | +8.5% | +3 |
| AAVE perp | +8.1% | +1 |
| AVAX perp | +7.6% | +7 |
| LINK perp | +7.3% | +1 |
| BCH perp | +7.1% | +2 |
| SOL perp | +6.4% | +1 |
| LTC perp | +3.7% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
