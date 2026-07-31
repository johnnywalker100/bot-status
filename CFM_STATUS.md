# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9694** (-3.06% since start) |
| Peak / drawdown | 1.0141 / -4.41% |
| Ticks recorded | 181 |
| Last tick | 2026-07-31T15:08:46.450468+00:00 (-0.1179%) |
| Risk rails | normal (dd -4.4%) |
| Data source | coinbase-cfm (bar 2026-07-31 14:00:00+00:00) |
| Gross leverage | 2.95x |
| Weeks tracked | 1 |
| Average week | +4.87% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.87% / +4.87% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +20.8% | +12 |
| AAVE perp | +19.9% | +4 |
| XLM perp | +17.9% | +2 |
| DOT perp | +10.9% | +14 |
| ETH perp | +9.6% | +5 |
| SOL perp | +7.5% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.0% | -14 |
| LTC perp | -39.3% | -17 |
| BNB perp | -24.2% | -4 |
| BCH perp | -23.4% | -11 |
| ZEC perp | -18.8% | -4 |
| LINK perp | -16.7% | -4 |
| BTC perp | -12.9% | -2 |
| AVAX perp | -9.2% | -14 |
| NEAR perp | -8.6% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
