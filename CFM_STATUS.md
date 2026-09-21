# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9220** (-7.80% since start) |
| Peak / drawdown | 1.0141 / -9.09% |
| Ticks recorded | 1409 |
| Last tick | 2026-09-21T04:08:39.751701+00:00 (-0.0787%) |
| Risk rails | normal (dd -9.1%) |
| Data source | coinbase-cfm (bar 2026-09-21 03:00:00+00:00) |
| Gross leverage | 0.94x |
| Weeks tracked | 9 |
| Average week | +0.00% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.4% | +1 |
| SOL perp | +12.1% | +2 |
| XLM perp | +10.7% | +1 |
| DOT perp | +10.0% | +8 |
| AAVE perp | +7.5% | +1 |
| LINK perp | +6.9% | +1 |
| AVAX perp | +6.1% | +5 |
| ETH perp | +5.8% | +2 |
| BCH perp | +5.5% | +2 |
| LTC perp | +3.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -9.6% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
