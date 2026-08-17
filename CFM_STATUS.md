# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9029** (-9.71% since start) |
| Peak / drawdown | 1.0141 / -10.96% |
| Ticks recorded | 575 |
| Last tick | 2026-08-17T04:11:22.265686+00:00 (-0.0640%) |
| Risk rails | normal (dd -11.0%) |
| Data source | coinbase-cfm (bar 2026-08-17 03:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 4 |
| Average week | -0.58% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +17.7% | +9 |
| XLM perp | +17.6% | +2 |
| ETH perp | +14.8% | +7 |
| AVAX perp | +7.1% | +10 |
| BCH perp | +6.8% | +3 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -49.2% | -7 |
| DOGE perp | -46.6% | -12 |
| LTC perp | -39.2% | -16 |
| NEAR perp | -36.0% | -4 |
| LINK perp | -21.0% | -4 |
| DOT perp | -11.9% | -14 |
| XRP perp | -11.1% | -2 |
| ZEC perp | -10.9% | -2 |
| SOL perp | -8.4% | -2 |
| AAVE perp | -4.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
