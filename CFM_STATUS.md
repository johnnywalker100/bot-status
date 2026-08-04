# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9393** (-6.07% since start) |
| Peak / drawdown | 1.0141 / -7.37% |
| Ticks recorded | 275 |
| Last tick | 2026-08-04T14:08:30.401436+00:00 (-0.1372%) |
| Risk rails | normal (dd -7.4%) |
| Data source | coinbase-cfm (bar 2026-08-04 13:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 2 |
| Average week | +0.81% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.12% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +29.7% | +15 |
| XLM perp | +18.0% | +2 |
| SOL perp | +15.7% | +4 |
| AAVE perp | +14.6% | +3 |
| ADA perp | +8.2% | +4 |
| AVAX perp | +5.7% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -37.6% | -6 |
| LTC perp | -35.3% | -15 |
| DOGE perp | -29.8% | -8 |
| BCH perp | -22.8% | -10 |
| ZEC perp | -20.7% | -4 |
| BTC perp | -13.6% | -2 |
| DOT perp | -13.2% | -15 |
| LINK perp | -13.1% | -3 |
| XRP perp | -11.4% | -2 |
| NEAR perp | -9.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
