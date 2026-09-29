# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9208** (-7.92% since start) |
| Peak / drawdown | 1.0141 / -9.20% |
| Ticks recorded | 1599 |
| Last tick | 2026-09-29T03:08:31.048096+00:00 (-0.4249%) |
| Risk rails | normal (dd -9.2%) |
| Data source | coinbase-cfm (bar 2026-09-29 02:00:00+00:00) |
| Gross leverage | 0.85x |
| Weeks tracked | 10 |
| Average week | +0.01% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -4.54% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +14.9% | +1 |
| ETH perp | +11.6% | +4 |
| DOT perp | +11.2% | +9 |
| BTC perp | +9.0% | +1 |
| AAVE perp | +8.0% | +1 |
| BCH perp | +6.6% | +2 |
| SOL perp | +6.4% | +1 |
| AVAX perp | +5.6% | +5 |
| LTC perp | +3.7% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
