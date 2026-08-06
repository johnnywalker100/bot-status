# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9154** (-8.46% since start) |
| Peak / drawdown | 1.0141 / -9.74% |
| Ticks recorded | 311 |
| Last tick | 2026-08-06T02:08:19.386089+00:00 (-0.4155%) |
| Risk rails | normal (dd -9.7%) |
| Data source | coinbase-cfm (bar 2026-08-06 01:00:00+00:00) |
| Gross leverage | 3.08x |
| Weeks tracked | 2 |
| Average week | -0.46% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.67% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +37.5% | +18 |
| XLM perp | +26.5% | +3 |
| AAVE perp | +19.4% | +4 |
| ADA perp | +10.4% | +5 |
| SOL perp | +8.0% | +2 |
| LTC perp | +7.4% | +3 |
| BTC perp | +7.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -41.9% | -11 |
| BCH perp | -39.7% | -17 |
| NEAR perp | -28.1% | -3 |
| BNB perp | -25.9% | -4 |
| ZEC perp | -22.2% | -4 |
| DOT perp | -15.6% | -17 |
| XRP perp | -11.5% | -2 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.2% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
