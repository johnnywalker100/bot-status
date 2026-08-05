# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9143** (-8.57% since start) |
| Peak / drawdown | 1.0141 / -9.84% |
| Ticks recorded | 304 |
| Last tick | 2026-08-05T19:08:55.299712+00:00 (-0.2588%) |
| Risk rails | normal (dd -9.8%) |
| Data source | coinbase-cfm (bar 2026-08-05 18:00:00+00:00) |
| Gross leverage | 3.14x |
| Weeks tracked | 2 |
| Average week | -0.52% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.78% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.6% | +16 |
| XLM perp | +27.5% | +3 |
| AAVE perp | +19.8% | +4 |
| SOL perp | +16.3% | +4 |
| ADA perp | +14.6% | +7 |
| BTC perp | +7.1% | +1 |
| AVAX perp | +5.1% | +7 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.6% | -9 |
| BCH perp | -23.6% | -10 |
| XRP perp | -23.4% | -4 |
| ZEC perp | -22.8% | -4 |
| LTC perp | -22.3% | -9 |
| BNB perp | -19.7% | -3 |
| LINK perp | -18.0% | -4 |
| DOT perp | -15.9% | -17 |
| NEAR perp | -9.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
