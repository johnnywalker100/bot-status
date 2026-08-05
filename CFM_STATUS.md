# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9204** (-7.96% since start) |
| Peak / drawdown | 1.0141 / -9.24% |
| Ticks recorded | 296 |
| Last tick | 2026-08-05T11:09:23.138784+00:00 (-0.0802%) |
| Risk rails | normal (dd -9.2%) |
| Data source | coinbase-cfm (bar 2026-08-05 10:00:00+00:00) |
| Gross leverage | 3.11x |
| Weeks tracked | 2 |
| Average week | -0.20% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.13% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.5% | +17 |
| XLM perp | +27.1% | +3 |
| AAVE perp | +19.8% | +4 |
| SOL perp | +16.1% | +4 |
| ADA perp | +14.9% | +7 |
| BTC perp | +7.0% | +1 |
| AVAX perp | +4.4% | +6 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.1% | -9 |
| BCH perp | -23.2% | -10 |
| XRP perp | -23.1% | -4 |
| ZEC perp | -22.4% | -4 |
| LTC perp | -21.9% | -9 |
| BNB perp | -19.5% | -3 |
| LINK perp | -17.8% | -4 |
| DOT perp | -15.7% | -17 |
| NEAR perp | -9.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
