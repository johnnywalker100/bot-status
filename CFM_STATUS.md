# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9423** (-5.77% since start) |
| Peak / drawdown | 1.0141 / -7.09% |
| Ticks recorded | 1596 |
| Last tick | 2026-09-29T00:08:50.917300+00:00 (+0.3144%) |
| Risk rails | normal (dd -7.1%) |
| Data source | coinbase-cfm (bar 2026-09-28 23:00:00+00:00) |
| Gross leverage | 0.87x |
| Weeks tracked | 10 |
| Average week | +0.23% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +15.8% | +1 |
| ETH perp | +11.4% | +4 |
| DOT perp | +11.3% | +9 |
| BTC perp | +8.9% | +1 |
| AVAX perp | +7.9% | +7 |
| AAVE perp | +7.9% | +1 |
| BCH perp | +6.6% | +2 |
| SOL perp | +6.3% | +1 |
| LTC perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |
| ADA perp | -2.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
