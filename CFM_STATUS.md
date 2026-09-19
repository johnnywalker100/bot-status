# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9145** (-8.55% since start) |
| Peak / drawdown | 1.0141 / -9.82% |
| Ticks recorded | 1373 |
| Last tick | 2026-09-19T15:08:22.178773+00:00 (+0.1781%) |
| Risk rails | normal (dd -9.8%) |
| Data source | coinbase-cfm (bar 2026-09-19 14:00:00+00:00) |
| Gross leverage | 0.79x |
| Weeks tracked | 8 |
| Average week | -0.10% |
| Weeks >= +3% | 12% |
| Best / worst week | +5.30% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.7% | +1 |
| SOL perp | +12.3% | +2 |
| XLM perp | +10.9% | +1 |
| DOT perp | +8.7% | +7 |
| AVAX perp | +7.2% | +7 |
| LINK perp | +6.9% | +1 |
| BCH perp | +5.6% | +2 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.9% | -1 |
| LTC perp | -3.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
