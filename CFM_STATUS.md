# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9182** (-8.18% since start) |
| Peak / drawdown | 1.0141 / -9.46% |
| Ticks recorded | 487 |
| Last tick | 2026-08-13T11:08:38.527816+00:00 (+0.0435%) |
| Risk rails | normal (dd -9.5%) |
| Data source | coinbase-cfm (bar 2026-08-13 10:00:00+00:00) |
| Gross leverage | 3.04x |
| Weeks tracked | 3 |
| Average week | -0.21% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.7% | +14 |
| AAVE perp | +24.1% | +5 |
| LTC perp | +21.9% | +9 |
| SOL perp | +16.5% | +4 |
| XLM perp | +8.8% | +1 |
| AVAX perp | +6.4% | +9 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.2% | -10 |
| BCH perp | -32.5% | -14 |
| BTC perp | -20.8% | -3 |
| BNB perp | -19.9% | -3 |
| LINK perp | -19.0% | -4 |
| NEAR perp | -18.1% | -2 |
| DOT perp | -16.8% | -20 |
| ADA perp | -16.1% | -8 |
| XRP perp | -11.0% | -2 |
| ZEC perp | -5.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
