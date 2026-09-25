# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9526** (-4.74% since start) |
| Peak / drawdown | 1.0141 / -6.06% |
| Ticks recorded | 1522 |
| Last tick | 2026-09-25T22:08:42.459585+00:00 (-0.2979%) |
| Risk rails | normal (dd -6.1%) |
| Data source | coinbase-cfm (bar 2026-09-25 21:00:00+00:00) |
| Gross leverage | 0.95x |
| Weeks tracked | 9 |
| Average week | +0.37% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.1% | +1 |
| XLM perp | +11.5% | +1 |
| DOT perp | +11.3% | +9 |
| ETH perp | +8.5% | +3 |
| AAVE perp | +8.0% | +1 |
| AVAX perp | +7.7% | +7 |
| LINK perp | +7.2% | +1 |
| BCH perp | +7.1% | +2 |
| SOL perp | +6.4% | +1 |
| LTC perp | +3.7% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
