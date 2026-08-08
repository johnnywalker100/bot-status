# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9255** (-7.45% since start) |
| Peak / drawdown | 1.0141 / -8.73% |
| Ticks recorded | 378 |
| Last tick | 2026-08-08T22:09:06.480167+00:00 (+0.1104%) |
| Risk rails | normal (dd -8.7%) |
| Data source | coinbase-cfm (bar 2026-08-08 21:00:00+00:00) |
| Gross leverage | 2.74x |
| Weeks tracked | 2 |
| Average week | +0.08% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.58% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.1% | +15 |
| AAVE perp | +24.7% | +5 |
| ADA perp | +12.9% | +6 |
| XLM perp | +8.9% | +1 |
| SOL perp | +8.2% | +2 |
| LTC perp | +7.5% | +3 |
| XRP perp | +5.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.9% | -12 |
| BNB perp | -39.0% | -6 |
| BCH perp | -35.1% | -15 |
| ZEC perp | -16.5% | -3 |
| DOT perp | -14.1% | -16 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.8% | -1 |
| AVAX perp | -6.3% | -9 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
