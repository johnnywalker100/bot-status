# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9390** (-6.10% since start) |
| Peak / drawdown | 1.0141 / -7.41% |
| Ticks recorded | 325 |
| Last tick | 2026-08-06T16:08:22.587648+00:00 (+0.1244%) |
| Risk rails | normal (dd -7.4%) |
| Data source | coinbase-cfm (bar 2026-08-06 15:00:00+00:00) |
| Gross leverage | 2.84x |
| Weeks tracked | 2 |
| Average week | +0.79% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.15% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.6% | +17 |
| XLM perp | +25.8% | +3 |
| AAVE perp | +18.9% | +4 |
| ADA perp | +8.8% | +4 |
| SOL perp | +7.8% | +2 |
| LTC perp | +7.3% | +3 |
| BTC perp | +6.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -38.7% | -17 |
| DOGE perp | -36.8% | -10 |
| NEAR perp | -26.8% | -3 |
| ZEC perp | -21.0% | -4 |
| BNB perp | -18.9% | -3 |
| DOT perp | -14.0% | -16 |
| XRP perp | -11.2% | -2 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.1% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
