# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9532** (-4.68% since start) |
| Peak / drawdown | 1.0141 / -6.01% |
| Ticks recorded | 191 |
| Last tick | 2026-08-01T02:08:48.327590+00:00 (-0.1425%) |
| Risk rails | normal (dd -6.0%) |
| Data source | coinbase-cfm (bar 2026-08-01 01:00:00+00:00) |
| Gross leverage | 3.07x |
| Weeks tracked | 1 |
| Average week | +3.12% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.12% / +3.12% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.5% | +4 |
| XLM perp | +18.1% | +2 |
| ETH perp | +15.7% | +8 |
| DOT perp | +14.4% | +18 |
| ADA perp | +14.2% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.5% | -14 |
| BNB perp | -30.9% | -5 |
| LTC perp | -30.2% | -13 |
| BCH perp | -28.7% | -13 |
| ZEC perp | -24.2% | -5 |
| LINK perp | -17.2% | -4 |
| BTC perp | -13.2% | -2 |
| NEAR perp | -8.8% | -1 |
| SOL perp | -7.7% | -2 |
| AVAX perp | -6.7% | -10 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
