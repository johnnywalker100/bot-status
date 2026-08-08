# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9299** (-7.01% since start) |
| Peak / drawdown | 1.0141 / -8.30% |
| Ticks recorded | 364 |
| Last tick | 2026-08-08T08:09:28.313232+00:00 (+0.0350%) |
| Risk rails | normal (dd -8.3%) |
| Data source | coinbase-cfm (bar 2026-08-08 07:00:00+00:00) |
| Gross leverage | 2.60x |
| Weeks tracked | 2 |
| Average week | +0.31% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.12% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.8% | +14 |
| AAVE perp | +24.2% | +5 |
| ADA perp | +12.9% | +6 |
| XLM perp | +8.8% | +1 |
| SOL perp | +8.0% | +2 |
| LTC perp | +7.3% | +3 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.3% | -12 |
| BNB perp | -38.3% | -6 |
| BCH perp | -32.6% | -14 |
| ZEC perp | -16.3% | -3 |
| DOT perp | -14.1% | -16 |
| LINK perp | -8.9% | -2 |
| NEAR perp | -8.6% | -1 |
| AVAX perp | -5.6% | -8 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
