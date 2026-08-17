# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9011** (-9.89% since start) |
| Peak / drawdown | 1.0141 / -11.15% |
| Ticks recorded | 577 |
| Last tick | 2026-08-17T06:09:08.199503+00:00 (+0.1135%) |
| Risk rails | normal (dd -11.1%) |
| Data source | coinbase-cfm (bar 2026-08-17 05:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 4 |
| Average week | -0.63% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.55% |

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
| BTC perp | -49.3% | -7 |
| DOGE perp | -46.7% | -12 |
| LTC perp | -39.2% | -16 |
| NEAR perp | -36.3% | -4 |
| LINK perp | -20.9% | -4 |
| DOT perp | -11.9% | -14 |
| XRP perp | -11.1% | -2 |
| ZEC perp | -11.0% | -2 |
| SOL perp | -8.4% | -2 |
| AAVE perp | -4.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
