# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9082** (-9.18% since start) |
| Peak / drawdown | 1.0141 / -10.44% |
| Ticks recorded | 314 |
| Last tick | 2026-08-06T05:09:32.941928+00:00 (-0.1552%) |
| Risk rails | normal (dd -10.4%) |
| Data source | coinbase-cfm (bar 2026-08-06 04:00:00+00:00) |
| Gross leverage | 2.84x |
| Weeks tracked | 2 |
| Average week | -0.84% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.42% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.7% | +16 |
| XLM perp | +26.9% | +3 |
| AAVE perp | +19.7% | +4 |
| ADA perp | +10.4% | +5 |
| SOL perp | +8.2% | +2 |
| LTC perp | +7.4% | +3 |
| BTC perp | +7.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.6% | -10 |
| BCH perp | -38.0% | -16 |
| ZEC perp | -22.6% | -4 |
| BNB perp | -19.7% | -3 |
| NEAR perp | -19.0% | -2 |
| DOT perp | -13.9% | -15 |
| XRP perp | -11.6% | -2 |
| LINK perp | -4.5% | -1 |
| AVAX perp | -2.2% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
