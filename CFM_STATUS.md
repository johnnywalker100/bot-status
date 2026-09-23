# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9534** (-4.66% since start) |
| Peak / drawdown | 1.0141 / -5.98% |
| Ticks recorded | 1455 |
| Last tick | 2026-09-23T02:08:26.591464+00:00 (-0.9112%) |
| Risk rails | normal (dd -6.0%) |
| Data source | coinbase-cfm (bar 2026-09-23 01:00:00+00:00) |
| Gross leverage | 0.97x |
| Weeks tracked | 9 |
| Average week | +0.38% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.9% | +1 |
| XLM perp | +11.3% | +1 |
| DOT perp | +11.2% | +9 |
| BNB perp | +8.3% | +1 |
| AAVE perp | +7.7% | +1 |
| BCH perp | +7.1% | +2 |
| LINK perp | +6.8% | +1 |
| SOL perp | +6.2% | +1 |
| ETH perp | +5.8% | +2 |
| DOGE perp | +5.3% | +1 |
| AVAX perp | +4.6% | +4 |
| LTC perp | +3.3% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
