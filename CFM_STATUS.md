# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9615** (-3.85% since start) |
| Peak / drawdown | 1.0141 / -5.19% |
| Ticks recorded | 203 |
| Last tick | 2026-08-01T14:08:41.091399+00:00 (-0.1968%) |
| Risk rails | normal (dd -5.2%) |
| Data source | coinbase-cfm (bar 2026-08-01 13:00:00+00:00) |
| Gross leverage | 3.05x |
| Weeks tracked | 1 |
| Average week | +4.01% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.01% / +4.01% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.0% | +4 |
| XLM perp | +17.9% | +2 |
| ETH perp | +15.6% | +8 |
| ADA perp | +14.6% | +8 |
| DOT perp | +14.4% | +18 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.1% | -14 |
| BNB perp | -30.2% | -5 |
| LTC perp | -29.9% | -13 |
| BCH perp | -28.2% | -13 |
| ZEC perp | -24.3% | -5 |
| LINK perp | -16.9% | -4 |
| BTC perp | -13.1% | -2 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -7.9% | -12 |
| SOL perp | -7.6% | -2 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
