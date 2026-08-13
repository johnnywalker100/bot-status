# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9178** (-8.22% since start) |
| Peak / drawdown | 1.0141 / -9.49% |
| Ticks recorded | 491 |
| Last tick | 2026-08-13T15:08:51.815273+00:00 (+0.1314%) |
| Risk rails | normal (dd -9.5%) |
| Data source | coinbase-cfm (bar 2026-08-13 14:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | -0.23% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.8% | +14 |
| AAVE perp | +24.1% | +5 |
| LTC perp | +22.0% | +9 |
| SOL perp | +12.5% | +3 |
| XLM perp | +8.8% | +1 |
| AVAX perp | +7.1% | +10 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.1% | -10 |
| BCH perp | -32.5% | -14 |
| BTC perp | -20.8% | -3 |
| BNB perp | -19.9% | -3 |
| LINK perp | -19.2% | -4 |
| NEAR perp | -18.0% | -2 |
| DOT perp | -16.9% | -20 |
| ADA perp | -14.0% | -7 |
| XRP perp | -11.0% | -2 |
| ZEC perp | -5.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
