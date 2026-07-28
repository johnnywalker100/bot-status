# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9441** (-5.59% since start) |
| Peak / drawdown | 1.0141 / -6.91% |
| Ticks recorded | 104 |
| Last tick | 2026-07-28T11:08:40.615458+00:00 (+0.1160%) |
| Risk rails | normal (dd -6.9%) |
| Data source | coinbase-cfm (bar 2026-07-28 10:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +2.13% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.13% / +2.13% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +30.7% | +6 |
| ADA perp | +23.2% | +14 |
| BCH perp | +13.5% | +6 |
| ETH perp | +9.9% | +5 |
| DOT perp | +8.1% | +10 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.2% | -13 |
| LTC perp | -34.4% | -14 |
| LINK perp | -26.3% | -6 |
| BNB perp | -23.9% | -4 |
| BTC perp | -20.1% | -3 |
| NEAR perp | -17.7% | -2 |
| ZEC perp | -14.8% | -3 |
| AVAX perp | -13.0% | -19 |
| XLM perp | -9.0% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
