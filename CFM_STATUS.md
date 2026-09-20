# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9083** (-9.17% since start) |
| Peak / drawdown | 1.0141 / -10.43% |
| Ticks recorded | 1382 |
| Last tick | 2026-09-20T01:08:26.237038+00:00 (-0.1432%) |
| Risk rails | normal (dd -10.4%) |
| Data source | coinbase-cfm (bar 2026-09-20 00:00:00+00:00) |
| Gross leverage | 0.82x |
| Weeks tracked | 8 |
| Average week | -0.19% |
| Weeks >= +3% | 12% |
| Best / worst week | +4.59% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.3% | +1 |
| SOL perp | +12.2% | +2 |
| XLM perp | +10.8% | +1 |
| DOT perp | +9.9% | +8 |
| BCH perp | +8.4% | +3 |
| LINK perp | +6.8% | +1 |
| AVAX perp | +6.6% | +6 |
| LTC perp | +3.2% | +1 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
