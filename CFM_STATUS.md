# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9216** (-7.84% since start) |
| Peak / drawdown | 1.0141 / -9.12% |
| Ticks recorded | 488 |
| Last tick | 2026-08-13T12:08:44.485543+00:00 (+0.3680%) |
| Risk rails | normal (dd -9.1%) |
| Data source | coinbase-cfm (bar 2026-08-13 11:00:00+00:00) |
| Gross leverage | 3.08x |
| Weeks tracked | 3 |
| Average week | -0.09% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.6% | +14 |
| AAVE perp | +24.0% | +5 |
| LTC perp | +21.8% | +9 |
| SOL perp | +16.4% | +4 |
| XLM perp | +8.7% | +1 |
| AVAX perp | +6.4% | +9 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.0% | -10 |
| BCH perp | -32.4% | -14 |
| LINK perp | -23.6% | -5 |
| BTC perp | -20.7% | -3 |
| BNB perp | -19.8% | -3 |
| NEAR perp | -17.9% | -2 |
| DOT perp | -17.5% | -21 |
| ADA perp | -15.9% | -8 |
| XRP perp | -10.9% | -2 |
| ZEC perp | -5.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
