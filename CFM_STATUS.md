# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9271** (-7.29% since start) |
| Peak / drawdown | 1.0141 / -8.58% |
| Ticks recorded | 419 |
| Last tick | 2026-08-10T15:08:26.984352+00:00 (-0.0101%) |
| Risk rails | normal (dd -8.6%) |
| Data source | coinbase-cfm (bar 2026-08-10 14:00:00+00:00) |
| Gross leverage | 2.23x |
| Weeks tracked | 3 |
| Average week | +0.11% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.5% | +14 |
| AAVE perp | +19.5% | +4 |
| LTC perp | +12.2% | +5 |
| XLM perp | +8.8% | +1 |
| BTC perp | +7.0% | +1 |
| AVAX perp | +5.6% | +8 |
| ADA perp | +4.2% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.9% | -13 |
| BCH perp | -25.4% | -11 |
| ZEC perp | -21.7% | -4 |
| BNB perp | -19.5% | -3 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.9% | -1 |
| DOT perp | -3.5% | -4 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
