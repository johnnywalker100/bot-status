# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8928** (-10.72% since start) |
| Peak / drawdown | 1.0141 / -11.96% |
| Ticks recorded | 1384 |
| Last tick | 2026-09-20T03:08:30.685874+00:00 (-1.3714%) |
| Risk rails | normal (dd -12.0%) |
| Data source | coinbase-cfm (bar 2026-09-20 02:00:00+00:00) |
| Gross leverage | 0.80x |
| Weeks tracked | 8 |
| Average week | -0.41% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.81% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.3% | +1 |
| SOL perp | +12.2% | +2 |
| XLM perp | +10.7% | +1 |
| DOT perp | +9.7% | +8 |
| BCH perp | +8.3% | +3 |
| LINK perp | +6.8% | +1 |
| AVAX perp | +5.4% | +5 |
| LTC perp | +3.2% | +1 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
