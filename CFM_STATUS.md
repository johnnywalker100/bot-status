# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9231** (-7.69% since start) |
| Peak / drawdown | 1.0141 / -8.98% |
| Ticks recorded | 1468 |
| Last tick | 2026-09-23T15:08:11.888646+00:00 (-2.2751%) |
| Risk rails | normal (dd -9.0%) |
| Data source | coinbase-cfm (bar 2026-09-23 14:00:00+00:00) |
| Gross leverage | 0.98x |
| Weeks tracked | 9 |
| Average week | +0.02% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +17.3% | +1 |
| XLM perp | +11.2% | +1 |
| DOT perp | +10.9% | +9 |
| BNB perp | +8.3% | +1 |
| AAVE perp | +7.7% | +1 |
| BCH perp | +7.4% | +2 |
| LINK perp | +6.7% | +1 |
| SOL perp | +6.2% | +1 |
| ETH perp | +5.8% | +2 |
| AVAX perp | +5.7% | +5 |
| DOGE perp | +5.1% | +1 |
| LTC perp | +3.3% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
