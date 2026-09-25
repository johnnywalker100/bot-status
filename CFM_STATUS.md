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
| Ticks recorded | 1511 |
| Last tick | 2026-09-25T10:08:20.426368+00:00 (-0.1450%) |
| Risk rails | normal (dd -6.2%) |
| Data source | coinbase-cfm (bar 2026-09-25 09:00:00+00:00) |
| Gross leverage | 0.92x |
| Weeks tracked | 9 |
| Average week | +0.36% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.6% | +1 |
| XLM perp | +11.6% | +1 |
| DOT perp | +11.1% | +9 |
| AAVE perp | +7.7% | +1 |
| AVAX perp | +7.6% | +7 |
| LINK perp | +7.4% | +1 |
| BCH perp | +7.1% | +2 |
| SOL perp | +6.2% | +1 |
| ETH perp | +5.7% | +2 |
| LTC perp | +3.7% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
