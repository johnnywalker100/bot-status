# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9523** (-4.77% since start) |
| Peak / drawdown | 1.0141 / -6.10% |
| Ticks recorded | 111 |
| Last tick | 2026-07-28T18:08:48.195704+00:00 (+0.9278%) |
| Risk rails | normal (dd -6.1%) |
| Data source | coinbase-cfm (bar 2026-07-28 17:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 1 |
| Average week | +3.02% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.02% / +3.02% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.3% | +5 |
| ADA perp | +23.4% | +14 |
| BCH perp | +13.4% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +7.2% | +9 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.9% | -14 |
| LTC perp | -34.0% | -14 |
| LINK perp | -26.3% | -6 |
| BNB perp | -23.9% | -4 |
| BTC perp | -20.1% | -3 |
| NEAR perp | -17.3% | -2 |
| ZEC perp | -14.7% | -3 |
| AVAX perp | -13.7% | -20 |
| XLM perp | -9.0% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
