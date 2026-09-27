# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9774** (-2.26% since start) |
| Peak / drawdown | 1.0141 / -3.62% |
| Ticks recorded | 1554 |
| Last tick | 2026-09-27T06:08:20.729818+00:00 (+0.6525%) |
| Risk rails | normal (dd -3.6%) |
| Data source | coinbase-cfm (bar 2026-09-27 05:00:00+00:00) |
| Gross leverage | 0.95x |
| Weeks tracked | 9 |
| Average week | +0.67% |
| Weeks >= +3% | 22% |
| Best / worst week | +6.35% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +17.0% | +1 |
| DOT perp | +11.4% | +9 |
| ETH perp | +11.1% | +4 |
| BTC perp | +8.6% | +1 |
| AAVE perp | +8.0% | +1 |
| AVAX perp | +7.8% | +7 |
| LINK perp | +7.3% | +1 |
| BCH perp | +6.9% | +2 |
| SOL perp | +6.2% | +1 |
| LTC perp | +3.7% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
