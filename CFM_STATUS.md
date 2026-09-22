# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9356** (-6.44% since start) |
| Peak / drawdown | 1.0141 / -7.75% |
| Ticks recorded | 1430 |
| Last tick | 2026-09-22T01:08:31.210344+00:00 (-0.4594%) |
| Risk rails | normal (dd -7.7%) |
| Data source | coinbase-cfm (bar 2026-09-22 00:00:00+00:00) |
| Gross leverage | 0.90x |
| Weeks tracked | 9 |
| Average week | +0.17% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +15.8% | +1 |
| SOL perp | +12.6% | +2 |
| DOT perp | +11.5% | +9 |
| XLM perp | +11.4% | +1 |
| AAVE perp | +7.7% | +1 |
| AVAX perp | +7.1% | +6 |
| LINK perp | +6.9% | +1 |
| LTC perp | +3.3% | +1 |
| ETH perp | +2.9% | +1 |
| BCH perp | +2.8% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
