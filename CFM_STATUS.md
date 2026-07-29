# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9733** (-2.67% since start) |
| Peak / drawdown | 1.0141 / -4.03% |
| Ticks recorded | 134 |
| Last tick | 2026-07-29T16:09:00.464227+00:00 (+0.1056%) |
| Risk rails | normal (dd -4.0%) |
| Data source | coinbase-cfm (bar 2026-07-29 15:00:00+00:00) |
| Gross leverage | 2.95x |
| Weeks tracked | 1 |
| Average week | +5.29% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.29% / +5.29% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.2% | +4 |
| ADA perp | +18.4% | +11 |
| XLM perp | +17.6% | +2 |
| BCH perp | +13.0% | +6 |
| ETH perp | +9.7% | +5 |
| DOT perp | +9.4% | +12 |
| SOL perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -46.8% | -13 |
| LTC perp | -36.9% | -16 |
| BNB perp | -29.2% | -5 |
| NEAR perp | -24.3% | -3 |
| BTC perp | -19.7% | -3 |
| LINK perp | -17.0% | -4 |
| ZEC perp | -14.3% | -3 |
| AVAX perp | -9.2% | -14 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
