# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9421** (-5.79% since start) |
| Peak / drawdown | 1.0141 / -7.11% |
| Ticks recorded | 109 |
| Last tick | 2026-07-28T16:08:52.437994+00:00 (-1.3350%) |
| Risk rails | normal (dd -7.1%) |
| Data source | coinbase-cfm (bar 2026-07-28 15:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 1 |
| Average week | +1.91% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.91% / +1.91% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.6% | +5 |
| ADA perp | +23.5% | +14 |
| BCH perp | +13.6% | +6 |
| ETH perp | +10.2% | +5 |
| DOT perp | +7.3% | +9 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.8% | -13 |
| LTC perp | -34.5% | -14 |
| LINK perp | -26.7% | -6 |
| BNB perp | -24.3% | -4 |
| BTC perp | -20.3% | -3 |
| NEAR perp | -17.6% | -2 |
| ZEC perp | -15.2% | -3 |
| AVAX perp | -13.2% | -19 |
| XLM perp | -9.1% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
