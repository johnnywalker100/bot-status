# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9293** (-7.07% since start) |
| Peak / drawdown | 1.0141 / -8.36% |
| Ticks recorded | 414 |
| Last tick | 2026-08-10T10:08:42.760232+00:00 (+0.1046%) |
| Risk rails | normal (dd -8.4%) |
| Data source | coinbase-cfm (bar 2026-08-10 09:00:00+00:00) |
| Gross leverage | 2.13x |
| Weeks tracked | 3 |
| Average week | +0.19% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +26.8% | +13 |
| AAVE perp | +14.7% | +3 |
| LTC perp | +12.2% | +5 |
| XLM perp | +8.8% | +1 |
| BTC perp | +7.0% | +1 |
| AVAX perp | +5.6% | +8 |
| ADA perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.9% | -13 |
| BCH perp | -25.5% | -11 |
| ZEC perp | -21.8% | -4 |
| BNB perp | -19.5% | -3 |
| LINK perp | -8.9% | -2 |
| NEAR perp | -8.9% | -1 |
| DOT perp | -2.6% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
