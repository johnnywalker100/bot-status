# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8823** (-11.77% since start) |
| Peak / drawdown | 1.0141 / -12.99% |
| Ticks recorded | 837 |
| Last tick | 2026-08-28T03:08:30.438611+00:00 (-0.0657%) |
| Risk rails | brake: drawdown -13.0% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-28 02:00:00+00:00) |
| Gross leverage | 0.12x |
| Weeks tracked | 5 |
| Average week | -0.92% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.54% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BCH perp | +3.0% | +1 |
| ETH perp | +2.8% | +1 |
| DOT perp | +2.0% | +2 |
| AVAX perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -2.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
