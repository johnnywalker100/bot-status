# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9223** (-7.77% since start) |
| Peak / drawdown | 1.0141 / -9.05% |
| Ticks recorded | 376 |
| Last tick | 2026-08-08T20:08:49.535512+00:00 (-0.1684%) |
| Risk rails | normal (dd -9.0%) |
| Data source | coinbase-cfm (bar 2026-08-08 19:00:00+00:00) |
| Gross leverage | 2.73x |
| Weeks tracked | 2 |
| Average week | -0.09% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.92% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.2% | +15 |
| AAVE perp | +24.8% | +5 |
| ADA perp | +13.0% | +6 |
| XLM perp | +8.9% | +1 |
| SOL perp | +8.3% | +2 |
| LTC perp | +7.5% | +3 |
| XRP perp | +5.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -46.2% | -12 |
| BNB perp | -39.2% | -6 |
| BCH perp | -32.9% | -14 |
| ZEC perp | -16.6% | -3 |
| DOT perp | -14.2% | -16 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.8% | -1 |
| AVAX perp | -6.4% | -9 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
