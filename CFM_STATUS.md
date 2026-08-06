# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9314** (-6.86% since start) |
| Peak / drawdown | 1.0141 / -8.16% |
| Ticks recorded | 322 |
| Last tick | 2026-08-06T13:09:28.634607+00:00 (-0.0041%) |
| Risk rails | normal (dd -8.2%) |
| Data source | coinbase-cfm (bar 2026-08-06 12:00:00+00:00) |
| Gross leverage | 2.80x |
| Weeks tracked | 2 |
| Average week | +0.39% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.96% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.5% | +17 |
| XLM perp | +25.7% | +3 |
| AAVE perp | +18.8% | +4 |
| ADA perp | +10.2% | +5 |
| SOL perp | +7.8% | +2 |
| LTC perp | +7.2% | +3 |
| BTC perp | +6.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -38.5% | -17 |
| DOGE perp | -36.8% | -10 |
| NEAR perp | -27.3% | -3 |
| ZEC perp | -21.0% | -4 |
| BNB perp | -19.1% | -3 |
| DOT perp | -14.0% | -16 |
| XRP perp | -5.6% | -1 |
| LINK perp | -4.3% | -1 |
| AVAX perp | -2.1% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
