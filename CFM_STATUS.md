# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9635** (-3.65% since start) |
| Peak / drawdown | 1.0141 / -4.99% |
| Ticks recorded | 204 |
| Last tick | 2026-08-01T15:08:24.406480+00:00 (+0.2165%) |
| Risk rails | normal (dd -5.0%) |
| Data source | coinbase-cfm (bar 2026-08-01 14:00:00+00:00) |
| Gross leverage | 3.04x |
| Weeks tracked | 1 |
| Average week | +4.24% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.24% / +4.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.1% | +4 |
| XLM perp | +17.8% | +2 |
| ETH perp | +15.5% | +8 |
| DOT perp | +14.5% | +18 |
| ADA perp | +14.4% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.9% | -14 |
| BNB perp | -30.0% | -5 |
| LTC perp | -29.8% | -13 |
| BCH perp | -28.0% | -13 |
| ZEC perp | -24.4% | -5 |
| LINK perp | -16.8% | -4 |
| BTC perp | -13.1% | -2 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -7.9% | -12 |
| SOL perp | -7.6% | -2 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
