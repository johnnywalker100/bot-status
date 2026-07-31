# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9614** (-3.86% since start) |
| Peak / drawdown | 1.0141 / -5.20% |
| Ticks recorded | 178 |
| Last tick | 2026-07-31T12:08:36.765535+00:00 (+0.2813%) |
| Risk rails | normal (dd -5.2%) |
| Data source | coinbase-cfm (bar 2026-07-31 11:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 1 |
| Average week | +4.01% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.01% / +4.01% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.1% | +12 |
| AAVE perp | +20.2% | +4 |
| XLM perp | +17.5% | +2 |
| DOT perp | +11.0% | +14 |
| ETH perp | +9.8% | +5 |
| SOL perp | +7.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.5% | -14 |
| LTC perp | -39.6% | -17 |
| BNB perp | -24.6% | -4 |
| BCH perp | -23.7% | -11 |
| ZEC perp | -19.1% | -4 |
| LINK perp | -17.1% | -4 |
| BTC perp | -13.3% | -2 |
| AVAX perp | -10.0% | -15 |
| NEAR perp | -8.5% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
