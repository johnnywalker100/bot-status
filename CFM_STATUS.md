# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9389** (-6.11% since start) |
| Peak / drawdown | 1.0141 / -7.41% |
| Ticks recorded | 97 |
| Last tick | 2026-07-28T04:08:35.782924+00:00 (-0.3064%) |
| Risk rails | normal (dd -7.4%) |
| Data source | coinbase-cfm (bar 2026-07-28 03:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 1 |
| Average week | +1.58% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.58% / +1.58% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.0% | +5 |
| ADA perp | +24.8% | +15 |
| BCH perp | +13.7% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +8.1% | +10 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.6% | -13 |
| LTC perp | -34.5% | -14 |
| LINK perp | -26.6% | -6 |
| BNB perp | -24.1% | -4 |
| BTC perp | -20.2% | -3 |
| NEAR perp | -17.9% | -2 |
| ZEC perp | -15.2% | -3 |
| AVAX perp | -12.3% | -18 |
| XLM perp | -9.2% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
