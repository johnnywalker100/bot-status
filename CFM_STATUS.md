# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9522** (-4.78% since start) |
| Peak / drawdown | 1.0141 / -6.11% |
| Ticks recorded | 1637 |
| Last tick | 2026-09-30T17:08:27.369993+00:00 (+0.3734%) |
| Risk rails | normal (dd -6.1%) |
| Data source | coinbase-cfm (bar 2026-09-30 16:00:00+00:00) |
| Gross leverage | 0.79x |
| Weeks tracked | 10 |
| Average week | +0.34% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +15.4% | +1 |
| ETH perp | +11.3% | +4 |
| BTC perp | +8.9% | +1 |
| AAVE perp | +8.5% | +1 |
| DOT perp | +7.9% | +6 |
| SOL perp | +6.3% | +1 |
| AVAX perp | +5.8% | +5 |
| LTC perp | +3.5% | +1 |
| BCH perp | +3.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |
| ADA perp | -2.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
