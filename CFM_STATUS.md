# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9354** (-6.46% since start) |
| Peak / drawdown | 1.0141 / -7.76% |
| Ticks recorded | 445 |
| Last tick | 2026-08-11T17:08:23.146580+00:00 (+0.4625%) |
| Risk rails | normal (dd -7.8%) |
| Data source | coinbase-cfm (bar 2026-08-11 16:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 3 |
| Average week | +0.40% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.8% | +17 |
| AAVE perp | +23.2% | +5 |
| XLM perp | +17.1% | +2 |
| LTC perp | +16.9% | +7 |
| BTC perp | +13.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -41.4% | -11 |
| BNB perp | -39.1% | -6 |
| BCH perp | -36.2% | -16 |
| ZEC perp | -30.0% | -6 |
| NEAR perp | -16.5% | -2 |
| ADA perp | -15.8% | -8 |
| DOT perp | -5.0% | -6 |
| LINK perp | -4.6% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
