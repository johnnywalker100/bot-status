# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9277** (-7.23% since start) |
| Peak / drawdown | 1.0141 / -8.52% |
| Ticks recorded | 365 |
| Last tick | 2026-08-08T09:08:47.942825+00:00 (-0.2354%) |
| Risk rails | normal (dd -8.5%) |
| Data source | coinbase-cfm (bar 2026-08-08 08:00:00+00:00) |
| Gross leverage | 2.61x |
| Weeks tracked | 2 |
| Average week | +0.19% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.35% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.9% | +14 |
| AAVE perp | +24.3% | +5 |
| ADA perp | +12.9% | +6 |
| XLM perp | +8.8% | +1 |
| SOL perp | +8.1% | +2 |
| LTC perp | +7.4% | +3 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.5% | -12 |
| BNB perp | -38.4% | -6 |
| BCH perp | -32.8% | -14 |
| ZEC perp | -16.4% | -3 |
| DOT perp | -14.1% | -16 |
| LINK perp | -8.9% | -2 |
| NEAR perp | -8.6% | -1 |
| AVAX perp | -5.6% | -8 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
