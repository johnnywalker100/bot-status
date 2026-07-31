# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9706** (-2.94% since start) |
| Peak / drawdown | 1.0141 / -4.29% |
| Ticks recorded | 180 |
| Last tick | 2026-07-31T14:08:42.168695+00:00 (+1.4811%) |
| Risk rails | normal (dd -4.3%) |
| Data source | coinbase-cfm (bar 2026-07-31 13:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 1 |
| Average week | +5.00% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.00% / +5.00% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +20.7% | +12 |
| AAVE perp | +19.9% | +4 |
| XLM perp | +17.4% | +2 |
| DOT perp | +11.6% | +15 |
| ETH perp | +11.4% | +6 |
| SOL perp | +7.5% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.6% | -14 |
| LTC perp | -39.2% | -17 |
| BNB perp | -24.1% | -4 |
| BCH perp | -23.3% | -11 |
| ZEC perp | -18.8% | -4 |
| LINK perp | -16.6% | -4 |
| BTC perp | -12.9% | -2 |
| AVAX perp | -9.8% | -15 |
| NEAR perp | -8.6% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
