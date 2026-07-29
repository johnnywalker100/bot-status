# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9684** (-3.16% since start) |
| Peak / drawdown | 1.0141 / -4.51% |
| Ticks recorded | 131 |
| Last tick | 2026-07-29T13:08:48.799245+00:00 (+0.1463%) |
| Risk rails | normal (dd -4.5%) |
| Data source | coinbase-cfm (bar 2026-07-29 12:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 1 |
| Average week | +4.76% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.76% / +4.76% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.2% | +4 |
| ADA perp | +18.6% | +11 |
| XLM perp | +18.0% | +2 |
| BCH perp | +13.1% | +6 |
| ETH perp | +9.8% | +5 |
| DOT perp | +9.4% | +12 |
| SOL perp | +3.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.3% | -13 |
| LTC perp | -37.3% | -16 |
| BNB perp | -29.4% | -5 |
| NEAR perp | -24.6% | -3 |
| BTC perp | -19.9% | -3 |
| LINK perp | -17.2% | -4 |
| ZEC perp | -14.2% | -3 |
| AVAX perp | -8.6% | -13 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
