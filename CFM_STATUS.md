# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9344** (-6.56% since start) |
| Peak / drawdown | 1.0141 / -7.86% |
| Ticks recorded | 357 |
| Last tick | 2026-08-08T01:08:23.758263+00:00 (+0.0563%) |
| Risk rails | normal (dd -7.8%) |
| Data source | coinbase-cfm (bar 2026-08-08 00:00:00+00:00) |
| Gross leverage | 2.53x |
| Weeks tracked | 2 |
| Average week | +0.55% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.64% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.7% | +14 |
| AAVE perp | +24.0% | +5 |
| ADA perp | +12.8% | +6 |
| XLM perp | +8.7% | +1 |
| SOL perp | +7.9% | +2 |
| LTC perp | +7.3% | +3 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.8% | -12 |
| BNB perp | -37.9% | -6 |
| BCH perp | -32.2% | -14 |
| DOT perp | -14.0% | -16 |
| ZEC perp | -10.8% | -2 |
| LINK perp | -8.7% | -2 |
| NEAR perp | -8.5% | -1 |
| AVAX perp | -6.2% | -9 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
