# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9660** (-3.40% since start) |
| Peak / drawdown | 1.0141 / -4.74% |
| Ticks recorded | 1459 |
| Last tick | 2026-09-23T06:08:30.051455+00:00 (+0.2371%) |
| Risk rails | normal (dd -4.7%) |
| Data source | coinbase-cfm (bar 2026-09-23 05:00:00+00:00) |
| Gross leverage | 0.98x |
| Weeks tracked | 9 |
| Average week | +0.54% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.7% | +1 |
| XLM perp | +11.4% | +1 |
| DOT perp | +11.1% | +9 |
| BNB perp | +8.2% | +1 |
| AAVE perp | +7.9% | +1 |
| BCH perp | +7.3% | +2 |
| LINK perp | +6.7% | +1 |
| SOL perp | +6.1% | +1 |
| AVAX perp | +5.8% | +5 |
| ETH perp | +5.7% | +2 |
| DOGE perp | +5.3% | +1 |
| LTC perp | +3.3% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
