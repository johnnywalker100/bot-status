# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9751** (-2.49% since start) |
| Peak / drawdown | 1.0141 / -3.85% |
| Ticks recorded | 211 |
| Last tick | 2026-08-01T22:08:43.741715+00:00 (-0.0103%) |
| Risk rails | normal (dd -3.8%) |
| Data source | coinbase-cfm (bar 2026-08-01 21:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 1 |
| Average week | +5.49% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.49% / +5.49% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +18.5% | +4 |
| XLM perp | +17.5% | +2 |
| ETH perp | +15.1% | +8 |
| DOT perp | +14.4% | +18 |
| ADA perp | +14.3% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -53.1% | -15 |
| BNB perp | -29.5% | -5 |
| LTC perp | -29.4% | -13 |
| BCH perp | -27.8% | -13 |
| ZEC perp | -23.7% | -5 |
| LINK perp | -16.5% | -4 |
| BTC perp | -12.9% | -2 |
| NEAR perp | -8.6% | -1 |
| SOL perp | -7.4% | -2 |
| AVAX perp | -6.3% | -10 |
| XRP perp | -5.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
