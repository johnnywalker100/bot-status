# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9220** (-7.80% since start) |
| Peak / drawdown | 1.0141 / -9.08% |
| Ticks recorded | 1601 |
| Last tick | 2026-09-29T05:08:27.559033+00:00 (+0.0079%) |
| Risk rails | normal (dd -9.1%) |
| Data source | coinbase-cfm (bar 2026-09-29 04:00:00+00:00) |
| Gross leverage | 0.85x |
| Weeks tracked | 10 |
| Average week | +0.02% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -4.42% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +14.8% | +1 |
| ETH perp | +11.6% | +4 |
| DOT perp | +11.2% | +9 |
| BTC perp | +9.0% | +1 |
| AAVE perp | +8.1% | +1 |
| BCH perp | +6.6% | +2 |
| SOL perp | +6.4% | +1 |
| AVAX perp | +5.7% | +5 |
| LTC perp | +3.7% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
