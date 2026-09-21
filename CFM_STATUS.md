# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9231** (-7.69% since start) |
| Peak / drawdown | 1.0141 / -8.98% |
| Ticks recorded | 1410 |
| Last tick | 2026-09-21T05:08:30.055330+00:00 (+0.1201%) |
| Risk rails | normal (dd -9.0%) |
| Data source | coinbase-cfm (bar 2026-09-21 04:00:00+00:00) |
| Gross leverage | 0.94x |
| Weeks tracked | 9 |
| Average week | +0.02% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.5% | +1 |
| SOL perp | +12.1% | +2 |
| XLM perp | +10.7% | +1 |
| DOT perp | +9.9% | +8 |
| AAVE perp | +7.5% | +1 |
| LINK perp | +6.8% | +1 |
| AVAX perp | +6.2% | +5 |
| ETH perp | +5.8% | +2 |
| BCH perp | +5.5% | +2 |
| LTC perp | +3.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -9.6% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
