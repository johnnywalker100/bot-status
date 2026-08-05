# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9196** (-8.04% since start) |
| Peak / drawdown | 1.0141 / -9.32% |
| Ticks recorded | 307 |
| Last tick | 2026-08-05T22:09:19.245900+00:00 (+0.4357%) |
| Risk rails | normal (dd -9.3%) |
| Data source | coinbase-cfm (bar 2026-08-05 21:00:00+00:00) |
| Gross leverage | 3.10x |
| Weeks tracked | 2 |
| Average week | -0.24% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.22% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.2% | +16 |
| XLM perp | +27.1% | +3 |
| AAVE perp | +19.6% | +4 |
| SOL perp | +16.1% | +4 |
| ADA perp | +14.5% | +7 |
| BTC perp | +7.0% | +1 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.3% | -9 |
| BCH perp | -23.3% | -10 |
| XRP perp | -23.1% | -4 |
| ZEC perp | -22.5% | -4 |
| LTC perp | -22.1% | -9 |
| BNB perp | -19.4% | -3 |
| LINK perp | -17.8% | -4 |
| DOT perp | -14.6% | -16 |
| NEAR perp | -9.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
