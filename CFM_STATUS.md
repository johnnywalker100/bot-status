# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9707** (-2.93% since start) |
| Peak / drawdown | 1.0141 / -4.28% |
| Ticks recorded | 138 |
| Last tick | 2026-07-29T20:09:02.658283+00:00 (+1.0597%) |
| Risk rails | normal (dd -4.3%) |
| Data source | coinbase-cfm (bar 2026-07-29 19:00:00+00:00) |
| Gross leverage | 2.95x |
| Weeks tracked | 1 |
| Average week | +5.01% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.01% / +5.01% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.8% | +4 |
| ADA perp | +18.5% | +11 |
| XLM perp | +17.4% | +2 |
| BCH perp | +14.8% | +7 |
| ETH perp | +9.7% | +5 |
| DOT perp | +9.4% | +12 |
| SOL perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -46.5% | -13 |
| LTC perp | -36.9% | -16 |
| BNB perp | -29.2% | -5 |
| NEAR perp | -24.6% | -3 |
| BTC perp | -19.6% | -3 |
| LINK perp | -16.9% | -4 |
| ZEC perp | -14.2% | -3 |
| AVAX perp | -8.5% | -13 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
