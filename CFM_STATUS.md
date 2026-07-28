# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9469** (-5.31% since start) |
| Peak / drawdown | 1.0141 / -6.63% |
| Ticks recorded | 106 |
| Last tick | 2026-07-28T13:09:00.317494+00:00 (+0.3833%) |
| Risk rails | normal (dd -6.6%) |
| Data source | coinbase-cfm (bar 2026-07-28 12:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 1 |
| Average week | +2.44% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.44% / +2.44% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +31.1% | +6 |
| ADA perp | +23.4% | +14 |
| BCH perp | +13.5% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +6.4% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.8% | -14 |
| LTC perp | -34.4% | -14 |
| LINK perp | -26.4% | -6 |
| BNB perp | -24.0% | -4 |
| BTC perp | -20.1% | -3 |
| NEAR perp | -17.6% | -2 |
| ZEC perp | -14.7% | -3 |
| AVAX perp | -14.3% | -21 |
| XLM perp | -9.1% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
