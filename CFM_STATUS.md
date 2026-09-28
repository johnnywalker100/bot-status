# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9418** (-5.82% since start) |
| Peak / drawdown | 1.0141 / -7.13% |
| Ticks recorded | 1588 |
| Last tick | 2026-09-28T16:08:26.475872+00:00 (+0.2624%) |
| Risk rails | normal (dd -7.1%) |
| Data source | coinbase-cfm (bar 2026-09-28 15:00:00+00:00) |
| Gross leverage | 0.87x |
| Weeks tracked | 10 |
| Average week | +0.23% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.3% | +1 |
| ETH perp | +11.4% | +4 |
| DOT perp | +11.2% | +9 |
| BTC perp | +8.9% | +1 |
| AAVE perp | +7.8% | +1 |
| AVAX perp | +7.7% | +7 |
| BCH perp | +6.6% | +2 |
| SOL perp | +6.3% | +1 |
| LTC perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |
| ADA perp | -2.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
