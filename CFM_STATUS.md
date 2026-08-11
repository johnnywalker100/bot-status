# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9224** (-7.76% since start) |
| Peak / drawdown | 1.0141 / -9.05% |
| Ticks recorded | 430 |
| Last tick | 2026-08-11T02:09:13.817288+00:00 (-0.2026%) |
| Risk rails | normal (dd -9.0%) |
| Data source | coinbase-cfm (bar 2026-08-11 01:00:00+00:00) |
| Gross leverage | 2.90x |
| Weeks tracked | 3 |
| Average week | -0.06% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.6% | +16 |
| AAVE perp | +24.2% | +5 |
| XLM perp | +17.6% | +2 |
| LTC perp | +14.7% | +6 |
| BTC perp | +6.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -39.1% | -6 |
| DOGE perp | -38.0% | -10 |
| BCH perp | -35.0% | -15 |
| ZEC perp | -26.6% | -5 |
| NEAR perp | -17.4% | -2 |
| ADA perp | -16.6% | -8 |
| XRP perp | -5.5% | -1 |
| DOT perp | -5.3% | -6 |
| LINK perp | -4.6% | -1 |
| SOL perp | -4.1% | -1 |
| AVAX perp | -1.4% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
