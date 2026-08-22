# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9075** (-9.25% since start) |
| Peak / drawdown | 1.0141 / -10.51% |
| Ticks recorded | 703 |
| Last tick | 2026-08-22T13:13:37.605624+00:00 (+0.0856%) |
| Risk rails | normal (dd -10.5%) |
| Data source | coinbase-cfm (bar 2026-08-22 12:00:00+00:00) |
| Gross leverage | 0.97x |
| Weeks tracked | 4 |
| Average week | -0.45% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +13.8% | +2 |
| XLM perp | +11.0% | +1 |
| BCH perp | +9.2% | +3 |
| BTC perp | +8.5% | +1 |
| BNB perp | +7.7% | +1 |
| DOT perp | +7.2% | +7 |
| LINK perp | +6.5% | +1 |
| ETH perp | +5.3% | +2 |
| SOL perp | +5.2% | +1 |
| ADA perp | +5.0% | +2 |
| AVAX perp | +4.2% | +5 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -10.5% | -1 |
| LTC perp | -2.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
