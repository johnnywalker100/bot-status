# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9331** (-6.69% since start) |
| Peak / drawdown | 1.0141 / -7.99% |
| Ticks recorded | 1495 |
| Last tick | 2026-09-24T18:08:43.531459+00:00 (-0.2789%) |
| Risk rails | normal (dd -8.0%) |
| Data source | coinbase-cfm (bar 2026-09-24 17:00:00+00:00) |
| Gross leverage | 0.89x |
| Weeks tracked | 9 |
| Average week | +0.14% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.6% | +1 |
| XLM perp | +11.3% | +1 |
| DOT perp | +11.2% | +9 |
| AAVE perp | +7.7% | +1 |
| BCH perp | +7.2% | +2 |
| LINK perp | +6.9% | +1 |
| SOL perp | +6.3% | +1 |
| ETH perp | +5.7% | +2 |
| DOGE perp | +5.1% | +1 |
| AVAX perp | +4.4% | +4 |
| LTC perp | +3.9% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
