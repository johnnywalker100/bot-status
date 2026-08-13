# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9230** (-7.70% since start) |
| Peak / drawdown | 1.0141 / -8.99% |
| Ticks recorded | 478 |
| Last tick | 2026-08-13T02:10:31.938848+00:00 (+0.1341%) |
| Risk rails | normal (dd -9.0%) |
| Data source | coinbase-cfm (bar 2026-08-13 01:00:00+00:00) |
| Gross leverage | 3.08x |
| Weeks tracked | 3 |
| Average week | -0.04% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.5% | +14 |
| AAVE perp | +23.8% | +5 |
| LTC perp | +21.8% | +9 |
| SOL perp | +16.4% | +4 |
| XLM perp | +8.7% | +1 |
| AVAX perp | +7.6% | +11 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -37.8% | -10 |
| BCH perp | -32.5% | -14 |
| LINK perp | -23.4% | -5 |
| BTC perp | -20.6% | -3 |
| BNB perp | -19.8% | -3 |
| NEAR perp | -17.8% | -2 |
| DOT perp | -17.5% | -21 |
| ADA perp | -15.7% | -8 |
| XRP perp | -10.9% | -2 |
| ZEC perp | -5.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
