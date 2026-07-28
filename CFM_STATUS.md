# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9494** (-5.06% since start) |
| Peak / drawdown | 1.0141 / -6.38% |
| Ticks recorded | 113 |
| Last tick | 2026-07-28T20:08:55.976067+00:00 (-0.2971%) |
| Risk rails | normal (dd -6.4%) |
| Data source | coinbase-cfm (bar 2026-07-28 19:00:00+00:00) |
| Gross leverage | 2.94x |
| Weeks tracked | 1 |
| Average week | +2.71% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.71% / +2.71% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.6% | +5 |
| ADA perp | +23.4% | +14 |
| BCH perp | +13.5% | +6 |
| ETH perp | +10.1% | +5 |
| DOT perp | +7.2% | +9 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.4% | -13 |
| LTC perp | -34.2% | -14 |
| LINK perp | -26.4% | -6 |
| BNB perp | -24.1% | -4 |
| BTC perp | -20.2% | -3 |
| NEAR perp | -17.3% | -2 |
| ZEC perp | -14.8% | -3 |
| AVAX perp | -13.2% | -19 |
| XLM perp | -9.1% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
