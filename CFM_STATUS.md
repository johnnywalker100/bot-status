# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9213** (-7.87% since start) |
| Peak / drawdown | 1.0141 / -9.15% |
| Ticks recorded | 280 |
| Last tick | 2026-08-04T19:09:27.475750+00:00 (-0.3630%) |
| Risk rails | normal (dd -9.1%) |
| Data source | coinbase-cfm (bar 2026-08-04 18:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 2 |
| Average week | -0.15% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.03% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.5% | +15 |
| XLM perp | +18.4% | +2 |
| AAVE perp | +14.7% | +3 |
| SOL perp | +12.1% | +3 |
| ADA perp | +8.3% | +4 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -38.7% | -6 |
| LTC perp | -36.4% | -15 |
| DOGE perp | -30.5% | -8 |
| ZEC perp | -22.0% | -4 |
| BCH perp | -20.9% | -9 |
| BTC perp | -14.0% | -2 |
| LINK perp | -13.4% | -3 |
| DOT perp | -12.8% | -14 |
| XRP perp | -11.7% | -2 |
| NEAR perp | -9.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
