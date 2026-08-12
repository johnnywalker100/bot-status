# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9084** (-9.16% since start) |
| Peak / drawdown | 1.0141 / -10.43% |
| Ticks recorded | 464 |
| Last tick | 2026-08-12T12:08:43.397807+00:00 (-0.4323%) |
| Risk rails | normal (dd -10.4%) |
| Data source | coinbase-cfm (bar 2026-08-12 11:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | -0.57% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.19% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.7% | +16 |
| AAVE perp | +24.7% | +5 |
| LTC perp | +20.0% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -40.3% | -17 |
| DOGE perp | -35.7% | -9 |
| BTC perp | -35.3% | -5 |
| ADA perp | -20.4% | -10 |
| BNB perp | -20.3% | -3 |
| DOT perp | -20.0% | -23 |
| ZEC perp | -16.2% | -3 |
| LINK perp | -14.6% | -3 |
| NEAR perp | -9.1% | -1 |
| XLM perp | -8.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
