# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8952** (-10.48% since start) |
| Peak / drawdown | 1.0141 / -11.72% |
| Ticks recorded | 689 |
| Last tick | 2026-08-21T23:09:59.019396+00:00 (-0.2038%) |
| Risk rails | normal (dd -11.7%) |
| Data source | coinbase-cfm (bar 2026-08-21 22:00:00+00:00) |
| Gross leverage | 1.73x |
| Weeks tracked | 4 |
| Average week | -0.79% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.19% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +27.1% | +4 |
| SOL perp | +15.8% | +3 |
| BNB perp | +15.4% | +2 |
| AVAX perp | +11.4% | +13 |
| XLM perp | +11.3% | +1 |
| ETH perp | +11.3% | +4 |
| BCH perp | +9.7% | +3 |
| ADA perp | +7.8% | +3 |
| DOT perp | +7.4% | +7 |
| LINK perp | +6.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -22.0% | -2 |
| DOGE perp | -20.9% | -4 |
| LTC perp | -6.0% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
