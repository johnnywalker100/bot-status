# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9017** (-9.83% since start) |
| Peak / drawdown | 1.0141 / -11.09% |
| Ticks recorded | 1489 |
| Last tick | 2026-09-24T12:08:40.576481+00:00 (-0.1575%) |
| Risk rails | normal (dd -11.1%) |
| Data source | coinbase-cfm (bar 2026-09-24 11:00:00+00:00) |
| Gross leverage | 0.89x |
| Weeks tracked | 9 |
| Average week | -0.24% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.5% | +1 |
| DOT perp | +11.1% | +9 |
| XLM perp | +11.1% | +1 |
| AAVE perp | +7.6% | +1 |
| BCH perp | +7.4% | +2 |
| LINK perp | +6.8% | +1 |
| SOL perp | +6.3% | +1 |
| ETH perp | +5.9% | +2 |
| DOGE perp | +5.1% | +1 |
| AVAX perp | +4.5% | +4 |
| LTC perp | +3.6% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
