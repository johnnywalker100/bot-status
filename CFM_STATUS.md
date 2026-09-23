# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9648** (-3.52% since start) |
| Peak / drawdown | 1.0141 / -4.86% |
| Ticks recorded | 1457 |
| Last tick | 2026-09-23T04:08:40.087802+00:00 (+0.3021%) |
| Risk rails | normal (dd -4.9%) |
| Data source | coinbase-cfm (bar 2026-09-23 03:00:00+00:00) |
| Gross leverage | 0.97x |
| Weeks tracked | 9 |
| Average week | +0.52% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.6% | +1 |
| XLM perp | +11.5% | +1 |
| DOT perp | +11.2% | +9 |
| BNB perp | +8.2% | +1 |
| AAVE perp | +7.8% | +1 |
| BCH perp | +7.0% | +2 |
| LINK perp | +6.8% | +1 |
| SOL perp | +6.2% | +1 |
| ETH perp | +5.7% | +2 |
| DOGE perp | +5.4% | +1 |
| AVAX perp | +4.7% | +4 |
| LTC perp | +3.3% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
