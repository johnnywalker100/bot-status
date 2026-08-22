# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9454** (-5.46% since start) |
| Peak / drawdown | 1.0141 / -6.77% |
| Ticks recorded | 695 |
| Last tick | 2026-08-22T05:08:56.829307+00:00 (-0.2781%) |
| Risk rails | normal (dd -6.8%) |
| Data source | coinbase-cfm (bar 2026-08-22 04:00:00+00:00) |
| Gross leverage | 1.44x |
| Weeks tracked | 4 |
| Average week | +0.58% |
| Weeks >= +3% | 25% |
| Best / worst week | +3.30% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.8% | +3 |
| BCH perp | +12.2% | +4 |
| DOT perp | +11.6% | +11 |
| XLM perp | +11.3% | +1 |
| SOL perp | +10.4% | +2 |
| ZEC perp | +8.6% | +1 |
| XRP perp | +8.6% | +1 |
| BTC perp | +8.3% | +1 |
| ETH perp | +7.9% | +3 |
| ADA perp | +7.8% | +3 |
| BNB perp | +7.6% | +1 |
| AVAX perp | +6.9% | +8 |
| LINK perp | +6.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -10.9% | -1 |
| LTC perp | -5.7% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
