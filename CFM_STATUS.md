# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9303** (-6.97% since start) |
| Peak / drawdown | 1.0141 / -8.27% |
| Ticks recorded | 85 |
| Last tick | 2026-07-27T16:08:38.032017+00:00 (+0.1419%) |
| Risk rails | normal (dd -8.3%) |
| Data source | coinbase-cfm (bar 2026-07-27 15:00:00+00:00) |
| Gross leverage | 2.93x |
| Weeks tracked | 1 |
| Average week | +0.64% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.64% / +0.64% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.5% | +5 |
| ADA perp | +25.5% | +15 |
| BCH perp | +20.8% | +9 |
| XLM perp | +18.9% | +2 |
| ETH perp | +10.4% | +5 |
| DOT perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.8% | -13 |
| LTC perp | -34.8% | -14 |
| LINK perp | -23.0% | -5 |
| BTC perp | -20.8% | -3 |
| ZEC perp | -20.8% | -4 |
| BNB perp | -18.3% | -3 |
| XRP perp | -11.7% | -2 |
| NEAR perp | -9.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
