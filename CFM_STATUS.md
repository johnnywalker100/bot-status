# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9358** (-6.42% since start) |
| Peak / drawdown | 1.0141 / -7.72% |
| Ticks recorded | 1422 |
| Last tick | 2026-09-21T17:08:53.096685+00:00 (-0.0452%) |
| Risk rails | normal (dd -7.7%) |
| Data source | coinbase-cfm (bar 2026-09-21 16:00:00+00:00) |
| Gross leverage | 0.91x |
| Weeks tracked | 9 |
| Average week | +0.17% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.0% | +1 |
| SOL perp | +12.6% | +2 |
| XLM perp | +11.2% | +1 |
| DOT perp | +10.2% | +8 |
| AAVE perp | +7.7% | +1 |
| LINK perp | +6.9% | +1 |
| AVAX perp | +5.9% | +5 |
| ETH perp | +5.9% | +2 |
| BCH perp | +5.7% | +2 |
| LTC perp | +3.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
