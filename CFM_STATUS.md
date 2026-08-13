# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9133** (-8.67% since start) |
| Peak / drawdown | 1.0141 / -9.94% |
| Ticks recorded | 484 |
| Last tick | 2026-08-13T08:14:26.212055+00:00 (-0.2552%) |
| Risk rails | normal (dd -9.9%) |
| Data source | coinbase-cfm (bar 2026-08-13 07:00:00+00:00) |
| Gross leverage | 2.94x |
| Weeks tracked | 3 |
| Average week | -0.39% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.67% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +29.0% | +14 |
| LTC perp | +22.1% | +9 |
| AAVE perp | +19.4% | +4 |
| SOL perp | +12.5% | +3 |
| XLM perp | +8.8% | +1 |
| AVAX perp | +7.8% | +11 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.7% | -9 |
| BCH perp | -33.0% | -14 |
| BTC perp | -20.9% | -3 |
| BNB perp | -20.1% | -3 |
| LINK perp | -19.1% | -4 |
| NEAR perp | -18.3% | -2 |
| DOT perp | -17.8% | -21 |
| ADA perp | -14.2% | -7 |
| XRP perp | -11.1% | -2 |
| ZEC perp | -5.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
