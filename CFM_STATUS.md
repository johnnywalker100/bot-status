# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8929** (-10.71% since start) |
| Peak / drawdown | 1.0141 / -11.95% |
| Ticks recorded | 690 |
| Last tick | 2026-08-22T00:08:44.763552+00:00 (-0.2611%) |
| Risk rails | normal (dd -12.0%) |
| Data source | coinbase-cfm (bar 2026-08-21 23:00:00+00:00) |
| Gross leverage | 1.71x |
| Weeks tracked | 4 |
| Average week | -0.85% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.44% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +27.5% | +4 |
| SOL perp | +15.6% | +3 |
| BNB perp | +15.1% | +2 |
| AVAX perp | +11.3% | +13 |
| XLM perp | +11.2% | +1 |
| ETH perp | +11.2% | +4 |
| BCH perp | +9.6% | +3 |
| ADA perp | +7.6% | +3 |
| DOT perp | +7.3% | +7 |
| LINK perp | +6.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -21.9% | -2 |
| DOGE perp | -20.3% | -4 |
| LTC perp | -5.9% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
