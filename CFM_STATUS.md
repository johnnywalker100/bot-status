# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9318** (-6.82% since start) |
| Peak / drawdown | 1.0141 / -8.11% |
| Ticks recorded | 1602 |
| Last tick | 2026-09-29T06:08:23.224924+00:00 (+1.0685%) |
| Risk rails | normal (dd -8.1%) |
| Data source | coinbase-cfm (bar 2026-09-29 05:00:00+00:00) |
| Gross leverage | 0.85x |
| Weeks tracked | 10 |
| Average week | +0.13% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -3.40% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +14.9% | +1 |
| ETH perp | +11.5% | +4 |
| DOT perp | +11.2% | +9 |
| BTC perp | +9.0% | +1 |
| AAVE perp | +8.3% | +1 |
| BCH perp | +6.6% | +2 |
| SOL perp | +6.4% | +1 |
| AVAX perp | +5.7% | +5 |
| LTC perp | +3.7% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
