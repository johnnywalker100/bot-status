# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9144** (-8.56% since start) |
| Peak / drawdown | 1.0141 / -9.83% |
| Ticks recorded | 458 |
| Last tick | 2026-08-12T06:08:35.701494+00:00 (+0.2918%) |
| Risk rails | normal (dd -9.8%) |
| Data source | coinbase-cfm (bar 2026-08-12 05:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 3 |
| Average week | -0.35% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.54% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.0% | +16 |
| AAVE perp | +24.5% | +5 |
| LTC perp | +19.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -39.6% | -17 |
| DOGE perp | -39.2% | -10 |
| BTC perp | -34.8% | -5 |
| ADA perp | -20.4% | -10 |
| BNB perp | -20.0% | -3 |
| DOT perp | -19.9% | -23 |
| ZEC perp | -15.9% | -3 |
| LINK perp | -14.3% | -3 |
| NEAR perp | -9.2% | -1 |
| XLM perp | -8.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
