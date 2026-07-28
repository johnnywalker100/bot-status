# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9522** (-4.78% since start) |
| Peak / drawdown | 1.0141 / -6.10% |
| Ticks recorded | 112 |
| Last tick | 2026-07-28T19:09:01.057205+00:00 (-0.0065%) |
| Risk rails | normal (dd -6.1%) |
| Data source | coinbase-cfm (bar 2026-07-28 18:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 1 |
| Average week | +3.01% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.01% / +3.01% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.5% | +5 |
| ADA perp | +23.3% | +14 |
| BCH perp | +13.4% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +7.2% | +9 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -52.0% | -14 |
| LTC perp | -34.0% | -14 |
| LINK perp | -26.3% | -6 |
| BNB perp | -23.9% | -4 |
| BTC perp | -20.1% | -3 |
| NEAR perp | -17.2% | -2 |
| ZEC perp | -14.7% | -3 |
| AVAX perp | -13.1% | -19 |
| XLM perp | -9.1% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
