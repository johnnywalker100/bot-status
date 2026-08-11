# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9223** (-7.77% since start) |
| Peak / drawdown | 1.0141 / -9.06% |
| Ticks recorded | 432 |
| Last tick | 2026-08-11T04:08:25.003044+00:00 (+0.1455%) |
| Risk rails | normal (dd -9.1%) |
| Data source | coinbase-cfm (bar 2026-08-11 03:00:00+00:00) |
| Gross leverage | 2.89x |
| Weeks tracked | 3 |
| Average week | -0.07% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.6% | +16 |
| AAVE perp | +24.1% | +5 |
| XLM perp | +17.5% | +2 |
| LTC perp | +14.7% | +6 |
| BTC perp | +6.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -39.1% | -6 |
| DOGE perp | -38.0% | -10 |
| BCH perp | -35.0% | -15 |
| ZEC perp | -26.8% | -5 |
| NEAR perp | -17.4% | -2 |
| ADA perp | -16.5% | -8 |
| XRP perp | -5.5% | -1 |
| DOT perp | -5.2% | -6 |
| LINK perp | -4.6% | -1 |
| SOL perp | -4.1% | -1 |
| AVAX perp | -1.4% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
