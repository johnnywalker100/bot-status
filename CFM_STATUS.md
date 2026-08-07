# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9286** (-7.14% since start) |
| Peak / drawdown | 1.0141 / -8.43% |
| Ticks recorded | 346 |
| Last tick | 2026-08-07T13:08:43.506654+00:00 (-0.0614%) |
| Risk rails | normal (dd -8.4%) |
| Data source | coinbase-cfm (bar 2026-08-07 12:00:00+00:00) |
| Gross leverage | 2.68x |
| Weeks tracked | 2 |
| Average week | +0.24% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.26% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +29.1% | +14 |
| ADA perp | +21.6% | +10 |
| XLM perp | +17.3% | +2 |
| SOL perp | +7.9% | +2 |
| XRP perp | +5.6% | +1 |
| AAVE perp | +4.8% | +1 |
| LTC perp | +2.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -46.7% | -20 |
| BNB perp | -38.3% | -6 |
| DOGE perp | -37.7% | -10 |
| ZEC perp | -16.5% | -3 |
| LINK perp | -13.4% | -3 |
| DOT perp | -13.2% | -15 |
| NEAR perp | -8.8% | -1 |
| AVAX perp | -4.9% | -7 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
