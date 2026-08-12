# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9173** (-8.27% since start) |
| Peak / drawdown | 1.0141 / -9.54% |
| Ticks recorded | 459 |
| Last tick | 2026-08-12T07:08:34.031727+00:00 (+0.3180%) |
| Risk rails | normal (dd -9.5%) |
| Data source | coinbase-cfm (bar 2026-08-12 06:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 3 |
| Average week | -0.24% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.9% | +16 |
| AAVE perp | +24.3% | +5 |
| LTC perp | +19.7% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -41.8% | -18 |
| DOGE perp | -35.1% | -9 |
| BTC perp | -34.7% | -5 |
| ADA perp | -20.2% | -10 |
| BNB perp | -20.0% | -3 |
| DOT perp | -19.8% | -23 |
| ZEC perp | -15.7% | -3 |
| LINK perp | -14.3% | -3 |
| NEAR perp | -9.0% | -1 |
| XLM perp | -8.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
