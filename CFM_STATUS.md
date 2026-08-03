# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9519** (-4.81% since start) |
| Peak / drawdown | 1.0141 / -6.14% |
| Ticks recorded | 247 |
| Last tick | 2026-08-03T10:08:24.956501+00:00 (-0.1083%) |
| Risk rails | normal (dd -6.1%) |
| Data source | coinbase-cfm (bar 2026-08-03 09:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 2 |
| Average week | +1.48% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +1.22% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.1% | +16 |
| XLM perp | +27.0% | +3 |
| SOL perp | +15.3% | +4 |
| ADA perp | +9.8% | +5 |
| AAVE perp | +4.8% | +1 |
| DOT perp | +3.4% | +4 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -37.2% | -16 |
| BNB perp | -36.9% | -6 |
| DOGE perp | -32.9% | -9 |
| BCH perp | -24.3% | -11 |
| ZEC perp | -20.0% | -4 |
| LINK perp | -17.3% | -4 |
| XRP perp | -16.9% | -3 |
| BTC perp | -13.2% | -2 |
| NEAR perp | -9.1% | -1 |
| AVAX perp | -3.4% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
