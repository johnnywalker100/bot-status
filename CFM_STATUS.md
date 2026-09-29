# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9425** (-5.75% since start) |
| Peak / drawdown | 1.0141 / -7.06% |
| Ticks recorded | 1612 |
| Last tick | 2026-09-29T16:08:27.249142+00:00 (-1.0343%) |
| Risk rails | normal (dd -7.1%) |
| Data source | coinbase-cfm (bar 2026-09-29 15:00:00+00:00) |
| Gross leverage | 0.85x |
| Weeks tracked | 10 |
| Average week | +0.24% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +14.7% | +1 |
| DOT perp | +11.3% | +9 |
| ETH perp | +11.3% | +4 |
| AAVE perp | +9.0% | +1 |
| BTC perp | +8.8% | +1 |
| BCH perp | +6.5% | +2 |
| SOL perp | +6.3% | +1 |
| AVAX perp | +5.9% | +5 |
| LTC perp | +3.6% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
