# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8926** (-10.74% since start) |
| Peak / drawdown | 1.0141 / -11.98% |
| Ticks recorded | 1353 |
| Last tick | 2026-09-18T18:08:13.382388+00:00 (+0.1598%) |
| Risk rails | normal (dd -11.9%) |
| Data source | coinbase-cfm (bar 2026-09-18 17:00:00+00:00) |
| Gross leverage | 0.78x |
| Weeks tracked | 8 |
| Average week | -0.42% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.78% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.3% | +1 |
| SOL perp | +12.6% | +2 |
| DOT perp | +10.2% | +8 |
| AVAX perp | +8.2% | +9 |
| AAVE perp | +7.7% | +1 |
| LINK perp | +6.8% | +1 |
| ETH perp | +2.9% | +1 |
| BCH perp | +2.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.9% | -1 |
| LTC perp | -3.2% | -1 |
| ADA perp | -2.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
