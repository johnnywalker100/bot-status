# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9123** (-8.77% since start) |
| Peak / drawdown | 1.0141 / -10.04% |
| Ticks recorded | 463 |
| Last tick | 2026-08-12T11:08:40.633305+00:00 (-0.0333%) |
| Risk rails | normal (dd -10.0%) |
| Data source | coinbase-cfm (bar 2026-08-12 10:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 3 |
| Average week | -0.42% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.77% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.5% | +16 |
| AAVE perp | +24.6% | +5 |
| LTC perp | +19.9% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -42.2% | -18 |
| DOGE perp | -35.5% | -9 |
| BTC perp | -35.1% | -5 |
| ADA perp | -20.4% | -10 |
| BNB perp | -20.2% | -3 |
| DOT perp | -19.9% | -23 |
| ZEC perp | -16.0% | -3 |
| LINK perp | -14.5% | -3 |
| NEAR perp | -9.0% | -1 |
| XLM perp | -8.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
