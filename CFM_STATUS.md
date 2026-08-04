# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9419** (-5.81% since start) |
| Peak / drawdown | 1.0141 / -7.12% |
| Ticks recorded | 269 |
| Last tick | 2026-08-04T08:09:14.544988+00:00 (-0.1424%) |
| Risk rails | normal (dd -7.1%) |
| Data source | coinbase-cfm (bar 2026-08-04 07:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 2 |
| Average week | +0.95% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.16% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +29.6% | +15 |
| XLM perp | +18.2% | +2 |
| SOL perp | +15.6% | +4 |
| AAVE perp | +14.8% | +3 |
| ADA perp | +8.3% | +4 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -37.5% | -6 |
| LTC perp | -35.2% | -15 |
| DOGE perp | -29.8% | -8 |
| BCH perp | -22.7% | -10 |
| ZEC perp | -20.7% | -4 |
| LINK perp | -17.3% | -4 |
| BTC perp | -13.5% | -2 |
| DOT perp | -13.3% | -15 |
| XRP perp | -11.4% | -2 |
| NEAR perp | -9.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
