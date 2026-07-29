# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9714** (-2.86% since start) |
| Peak / drawdown | 1.0141 / -4.21% |
| Ticks recorded | 121 |
| Last tick | 2026-07-29T04:08:50.711427+00:00 (+1.5146%) |
| Risk rails | normal (dd -4.2%) |
| Data source | coinbase-cfm (bar 2026-07-29 03:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 1 |
| Average week | +5.09% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.09% / +5.09% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.1% | +4 |
| ADA perp | +18.5% | +11 |
| XLM perp | +17.7% | +2 |
| BCH perp | +13.1% | +6 |
| DOT perp | +10.1% | +13 |
| ETH perp | +9.7% | +5 |
| SOL perp | +3.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -46.9% | -13 |
| LTC perp | -37.2% | -16 |
| BNB perp | -29.2% | -5 |
| NEAR perp | -24.7% | -3 |
| BTC perp | -19.6% | -3 |
| LINK perp | -17.1% | -4 |
| ZEC perp | -14.0% | -3 |
| AVAX perp | -8.5% | -13 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
