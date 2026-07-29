# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9577** (-4.23% since start) |
| Peak / drawdown | 1.0141 / -5.57% |
| Ticks recorded | 119 |
| Last tick | 2026-07-29T02:10:04.599605+00:00 (+0.8310%) |
| Risk rails | normal (dd -5.6%) |
| Data source | coinbase-cfm (bar 2026-07-29 01:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +3.60% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.60% / +3.60% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.9% | +4 |
| ADA perp | +18.6% | +11 |
| XLM perp | +18.1% | +2 |
| BCH perp | +13.4% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +9.5% | +12 |
| SOL perp | +3.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.8% | -13 |
| LTC perp | -38.4% | -16 |
| BNB perp | -29.8% | -5 |
| NEAR perp | -25.6% | -3 |
| BTC perp | -20.0% | -3 |
| LINK perp | -17.5% | -4 |
| ZEC perp | -14.4% | -3 |
| AVAX perp | -8.8% | -13 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
