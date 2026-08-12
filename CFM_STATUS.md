# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9177** (-8.23% since start) |
| Peak / drawdown | 1.0141 / -9.51% |
| Ticks recorded | 460 |
| Last tick | 2026-08-12T08:08:29.757581+00:00 (+0.0382%) |
| Risk rails | normal (dd -9.5%) |
| Data source | coinbase-cfm (bar 2026-08-12 07:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 3 |
| Average week | -0.23% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.0% | +16 |
| AAVE perp | +24.3% | +5 |
| LTC perp | +19.7% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -41.8% | -18 |
| DOGE perp | -39.0% | -10 |
| BTC perp | -34.7% | -5 |
| DOT perp | -20.6% | -24 |
| ADA perp | -20.2% | -10 |
| BNB perp | -20.0% | -3 |
| ZEC perp | -15.7% | -3 |
| LINK perp | -14.3% | -3 |
| NEAR perp | -9.0% | -1 |
| XLM perp | -8.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
