# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9290** (-7.10% since start) |
| Peak / drawdown | 1.0141 / -8.40% |
| Ticks recorded | 84 |
| Last tick | 2026-07-27T15:08:43.498344+00:00 (+1.0478%) |
| Risk rails | normal (dd -8.4%) |
| Data source | coinbase-cfm (bar 2026-07-27 14:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 1 |
| Average week | +0.50% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.50% / +0.50% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.7% | +5 |
| ADA perp | +25.7% | +15 |
| XLM perp | +18.9% | +2 |
| BCH perp | +18.5% | +8 |
| ETH perp | +10.4% | +5 |
| SOL perp | +4.1% | +1 |
| DOT perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.9% | -13 |
| LTC perp | -34.9% | -14 |
| LINK perp | -23.1% | -5 |
| ZEC perp | -21.1% | -4 |
| BTC perp | -20.9% | -3 |
| BNB perp | -18.3% | -3 |
| XRP perp | -11.7% | -2 |
| NEAR perp | -9.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
