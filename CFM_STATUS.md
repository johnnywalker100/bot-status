# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9722** (-2.78% since start) |
| Peak / drawdown | 1.0141 / -4.13% |
| Ticks recorded | 133 |
| Last tick | 2026-07-29T15:08:44.370876+00:00 (+0.5806%) |
| Risk rails | normal (dd -4.1%) |
| Data source | coinbase-cfm (bar 2026-07-29 14:00:00+00:00) |
| Gross leverage | 2.95x |
| Weeks tracked | 1 |
| Average week | +5.18% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.18% / +5.18% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.2% | +4 |
| ADA perp | +18.4% | +11 |
| XLM perp | +17.8% | +2 |
| BCH perp | +13.0% | +6 |
| ETH perp | +9.8% | +5 |
| DOT perp | +9.4% | +12 |
| SOL perp | +3.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -46.9% | -13 |
| LTC perp | -37.0% | -16 |
| BNB perp | -29.2% | -5 |
| NEAR perp | -24.5% | -3 |
| BTC perp | -19.8% | -3 |
| LINK perp | -17.0% | -4 |
| ZEC perp | -14.3% | -3 |
| AVAX perp | -8.5% | -13 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
