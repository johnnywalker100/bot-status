# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9343** (-6.57% since start) |
| Peak / drawdown | 1.0141 / -7.87% |
| Ticks recorded | 162 |
| Last tick | 2026-07-30T20:09:04.851218+00:00 (-0.1942%) |
| Risk rails | normal (dd -7.9%) |
| Data source | coinbase-cfm (bar 2026-07-30 19:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 1 |
| Average week | +1.08% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.08% / +1.08% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.1% | +12 |
| AAVE perp | +21.3% | +4 |
| ETH perp | +16.5% | +8 |
| DOT perp | +13.3% | +16 |
| XLM perp | +9.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.4% | -12 |
| LTC perp | -38.9% | -16 |
| NEAR perp | -27.2% | -3 |
| BNB perp | -25.4% | -4 |
| ZEC perp | -25.4% | -5 |
| LINK perp | -18.2% | -4 |
| BTC perp | -13.9% | -2 |
| AVAX perp | -9.0% | -13 |
| BCH perp | -7.0% | -3 |
| XRP perp | -5.8% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
