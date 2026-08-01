# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9812** (-1.88% since start) |
| Peak / drawdown | 1.0141 / -3.24% |
| Ticks recorded | 209 |
| Last tick | 2026-08-01T20:08:27.807235+00:00 (+0.2522%) |
| Risk rails | normal (dd -3.2%) |
| Data source | coinbase-cfm (bar 2026-08-01 19:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 1 |
| Average week | +6.15% |
| Weeks >= +3% | 100% |
| Best / worst week | +6.15% / +6.15% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +18.3% | +4 |
| XLM perp | +17.3% | +2 |
| ETH perp | +15.0% | +8 |
| DOT perp | +14.9% | +19 |
| ADA perp | +14.1% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -52.3% | -15 |
| BCH perp | -29.5% | -14 |
| BNB perp | -29.3% | -5 |
| LTC perp | -29.1% | -13 |
| ZEC perp | -23.6% | -5 |
| LINK perp | -16.3% | -4 |
| BTC perp | -12.7% | -2 |
| NEAR perp | -8.5% | -1 |
| SOL perp | -7.3% | -2 |
| AVAX perp | -6.2% | -10 |
| XRP perp | -5.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
