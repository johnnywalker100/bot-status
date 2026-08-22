# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9067** (-9.33% since start) |
| Peak / drawdown | 1.0141 / -10.59% |
| Ticks recorded | 691 |
| Last tick | 2026-08-22T01:08:29.840314+00:00 (+1.5452%) |
| Risk rails | normal (dd -10.5%) |
| Data source | coinbase-cfm (bar 2026-08-22 00:00:00+00:00) |
| Gross leverage | 1.83x |
| Weeks tracked | 4 |
| Average week | -0.47% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.5% | +3 |
| BTC perp | +17.2% | +2 |
| BCH perp | +16.3% | +5 |
| SOL perp | +15.6% | +3 |
| BNB perp | +15.2% | +2 |
| DOT perp | +15.1% | +14 |
| XLM perp | +11.2% | +1 |
| ADA perp | +10.2% | +4 |
| AVAX perp | +8.7% | +10 |
| ETH perp | +8.3% | +3 |
| XRP perp | +8.1% | +1 |
| ZEC perp | +8.1% | +1 |
| LINK perp | +6.7% | +1 |
| DOGE perp | +5.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -10.9% | -1 |
| LTC perp | -5.9% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
