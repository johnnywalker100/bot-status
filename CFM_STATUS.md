# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9051** (-9.49% since start) |
| Peak / drawdown | 1.0141 / -10.75% |
| Ticks recorded | 453 |
| Last tick | 2026-08-12T01:08:40.121299+00:00 (-0.6650%) |
| Risk rails | normal (dd -10.6%) |
| Data source | coinbase-cfm (bar 2026-08-12 00:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | -0.68% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.54% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.2% | +16 |
| AAVE perp | +24.5% | +5 |
| LTC perp | +20.1% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -40.2% | -17 |
| DOGE perp | -35.9% | -9 |
| BTC perp | -35.1% | -5 |
| ADA perp | -20.5% | -10 |
| BNB perp | -20.5% | -3 |
| DOT perp | -20.1% | -23 |
| ZEC perp | -16.0% | -3 |
| LINK perp | -14.5% | -3 |
| NEAR perp | -9.0% | -1 |
| XLM perp | -8.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
