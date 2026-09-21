# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9372** (-6.28% since start) |
| Peak / drawdown | 1.0141 / -7.58% |
| Ticks recorded | 1425 |
| Last tick | 2026-09-21T20:08:40.693001+00:00 (+0.7451%) |
| Risk rails | normal (dd -7.6%) |
| Data source | coinbase-cfm (bar 2026-09-21 19:00:00+00:00) |
| Gross leverage | 0.91x |
| Weeks tracked | 9 |
| Average week | +0.19% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +15.7% | +1 |
| SOL perp | +12.7% | +2 |
| XLM perp | +11.4% | +1 |
| DOT perp | +10.1% | +8 |
| AAVE perp | +7.8% | +1 |
| LINK perp | +7.0% | +1 |
| ETH perp | +5.9% | +2 |
| AVAX perp | +5.9% | +5 |
| BCH perp | +5.7% | +2 |
| LTC perp | +3.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
