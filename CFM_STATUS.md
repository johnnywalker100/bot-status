# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9297** (-7.03% since start) |
| Peak / drawdown | 1.0141 / -8.33% |
| Ticks recorded | 277 |
| Last tick | 2026-08-04T16:09:27.401766+00:00 (-0.2213%) |
| Risk rails | normal (dd -8.3%) |
| Data source | coinbase-cfm (bar 2026-08-04 15:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 2 |
| Average week | +0.30% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.14% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.2% | +15 |
| XLM perp | +18.2% | +2 |
| SOL perp | +15.9% | +4 |
| AAVE perp | +14.5% | +3 |
| ADA perp | +8.3% | +4 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -38.3% | -6 |
| LTC perp | -35.8% | -15 |
| DOGE perp | -30.1% | -8 |
| BCH perp | -22.9% | -10 |
| ZEC perp | -21.4% | -4 |
| BTC perp | -13.8% | -2 |
| LINK perp | -13.2% | -3 |
| DOT perp | -12.6% | -14 |
| XRP perp | -11.6% | -2 |
| NEAR perp | -9.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
