# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9590** (-4.10% since start) |
| Peak / drawdown | 1.0141 / -5.44% |
| Ticks recorded | 1464 |
| Last tick | 2026-09-23T11:08:36.924275+00:00 (+0.0973%) |
| Risk rails | normal (dd -5.4%) |
| Data source | coinbase-cfm (bar 2026-09-23 10:00:00+00:00) |
| Gross leverage | 0.98x |
| Weeks tracked | 9 |
| Average week | +0.45% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +17.2% | +1 |
| XLM perp | +11.3% | +1 |
| DOT perp | +10.9% | +9 |
| BNB perp | +8.2% | +1 |
| AAVE perp | +7.8% | +1 |
| BCH perp | +7.4% | +2 |
| LINK perp | +6.7% | +1 |
| SOL perp | +6.1% | +1 |
| AVAX perp | +5.9% | +5 |
| ETH perp | +5.7% | +2 |
| DOGE perp | +5.2% | +1 |
| LTC perp | +3.3% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
