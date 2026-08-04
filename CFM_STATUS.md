# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9317** (-6.83% since start) |
| Peak / drawdown | 1.0141 / -8.12% |
| Ticks recorded | 276 |
| Last tick | 2026-08-04T15:09:43.491295+00:00 (-0.8075%) |
| Risk rails | normal (dd -8.1%) |
| Data source | coinbase-cfm (bar 2026-08-04 14:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 2 |
| Average week | +0.41% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.92% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.1% | +15 |
| XLM perp | +18.2% | +2 |
| SOL perp | +15.8% | +4 |
| AAVE perp | +14.6% | +3 |
| ADA perp | +8.3% | +4 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -38.2% | -6 |
| LTC perp | -35.8% | -15 |
| DOGE perp | -30.1% | -8 |
| ZEC perp | -21.2% | -4 |
| BCH perp | -20.7% | -9 |
| BTC perp | -13.7% | -2 |
| DOT perp | -13.3% | -15 |
| LINK perp | -13.2% | -3 |
| XRP perp | -11.5% | -2 |
| NEAR perp | -9.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
