# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9247** (-7.53% since start) |
| Peak / drawdown | 1.0141 / -8.82% |
| Ticks recorded | 279 |
| Last tick | 2026-08-04T18:08:36.989172+00:00 (-0.2225%) |
| Risk rails | normal (dd -8.8%) |
| Data source | coinbase-cfm (bar 2026-08-04 17:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 2 |
| Average week | +0.03% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.68% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.4% | +15 |
| XLM perp | +18.4% | +2 |
| SOL perp | +16.0% | +4 |
| AAVE perp | +14.6% | +3 |
| ADA perp | +8.3% | +4 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -38.5% | -6 |
| LTC perp | -36.1% | -15 |
| DOGE perp | -30.4% | -8 |
| ZEC perp | -21.7% | -4 |
| BCH perp | -20.8% | -9 |
| BTC perp | -13.9% | -2 |
| LINK perp | -13.3% | -3 |
| DOT perp | -12.7% | -14 |
| XRP perp | -11.6% | -2 |
| NEAR perp | -9.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
