# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9400** (-6.00% since start) |
| Peak / drawdown | 1.0141 / -7.31% |
| Ticks recorded | 272 |
| Last tick | 2026-08-04T11:08:42.772548+00:00 (-0.2582%) |
| Risk rails | normal (dd -7.3%) |
| Data source | coinbase-cfm (bar 2026-08-04 10:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 2 |
| Average week | +0.84% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.05% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +29.8% | +15 |
| XLM perp | +18.1% | +2 |
| SOL perp | +15.6% | +4 |
| AAVE perp | +14.7% | +3 |
| ADA perp | +8.3% | +4 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -37.6% | -6 |
| LTC perp | -35.3% | -15 |
| DOGE perp | -29.9% | -8 |
| ZEC perp | -20.8% | -4 |
| BCH perp | -20.5% | -9 |
| BTC perp | -13.5% | -2 |
| DOT perp | -13.3% | -15 |
| LINK perp | -13.1% | -3 |
| XRP perp | -11.4% | -2 |
| NEAR perp | -9.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
