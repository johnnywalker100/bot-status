# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9246** (-7.54% since start) |
| Peak / drawdown | 1.0141 / -8.83% |
| Ticks recorded | 442 |
| Last tick | 2026-08-11T14:08:25.320854+00:00 (+0.2253%) |
| Risk rails | normal (dd -8.8%) |
| Data source | coinbase-cfm (bar 2026-08-11 13:00:00+00:00) |
| Gross leverage | 2.91x |
| Weeks tracked | 3 |
| Average week | +0.02% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.6% | +16 |
| AAVE perp | +24.0% | +5 |
| XLM perp | +17.4% | +2 |
| LTC perp | +14.6% | +6 |
| BTC perp | +6.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -39.6% | -6 |
| DOGE perp | -38.4% | -10 |
| BCH perp | -36.9% | -16 |
| ZEC perp | -26.1% | -5 |
| NEAR perp | -17.1% | -2 |
| ADA perp | -16.2% | -8 |
| XRP perp | -5.5% | -1 |
| DOT perp | -5.1% | -6 |
| LINK perp | -4.7% | -1 |
| SOL perp | -4.1% | -1 |
| AVAX perp | -1.4% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
