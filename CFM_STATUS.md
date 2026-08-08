# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9300** (-7.00% since start) |
| Peak / drawdown | 1.0141 / -8.30% |
| Ticks recorded | 370 |
| Last tick | 2026-08-08T14:09:36.918248+00:00 (+0.1533%) |
| Risk rails | normal (dd -8.3%) |
| Data source | coinbase-cfm (bar 2026-08-08 13:00:00+00:00) |
| Gross leverage | 2.71x |
| Weeks tracked | 2 |
| Average week | +0.31% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.11% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.0% | +15 |
| AAVE perp | +24.4% | +5 |
| ADA perp | +12.9% | +6 |
| XLM perp | +8.9% | +1 |
| SOL perp | +8.1% | +2 |
| LTC perp | +7.4% | +3 |
| XRP perp | +5.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.5% | -12 |
| BNB perp | -38.6% | -6 |
| BCH perp | -35.0% | -15 |
| ZEC perp | -16.2% | -3 |
| DOT perp | -14.0% | -16 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.6% | -1 |
| AVAX perp | -5.6% | -8 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
