# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9245** (-7.55% since start) |
| Peak / drawdown | 1.0141 / -8.84% |
| Ticks recorded | 377 |
| Last tick | 2026-08-08T21:08:45.285473+00:00 (+0.2354%) |
| Risk rails | normal (dd -8.8%) |
| Data source | coinbase-cfm (bar 2026-08-08 20:00:00+00:00) |
| Gross leverage | 2.74x |
| Weeks tracked | 2 |
| Average week | +0.02% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.69% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.1% | +15 |
| AAVE perp | +24.8% | +5 |
| ADA perp | +13.0% | +6 |
| XLM perp | +8.9% | +1 |
| SOL perp | +8.2% | +2 |
| LTC perp | +7.5% | +3 |
| XRP perp | +5.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -46.1% | -12 |
| BNB perp | -39.1% | -6 |
| BCH perp | -35.1% | -15 |
| ZEC perp | -16.5% | -3 |
| DOT perp | -14.2% | -16 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.8% | -1 |
| AVAX perp | -6.3% | -9 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
