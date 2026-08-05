# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9138** (-8.62% since start) |
| Peak / drawdown | 1.0141 / -9.89% |
| Ticks recorded | 288 |
| Last tick | 2026-08-05T03:08:17.777016+00:00 (+0.3640%) |
| Risk rails | normal (dd -9.9%) |
| Data source | coinbase-cfm (bar 2026-08-05 02:00:00+00:00) |
| Gross leverage | 3.15x |
| Weeks tracked | 2 |
| Average week | -0.55% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.83% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.9% | +17 |
| XLM perp | +27.5% | +3 |
| AAVE perp | +19.9% | +4 |
| SOL perp | +16.2% | +4 |
| ADA perp | +14.7% | +7 |
| BTC perp | +7.0% | +1 |
| AVAX perp | +4.4% | +6 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.5% | -9 |
| XRP perp | -23.5% | -4 |
| BCH perp | -23.3% | -10 |
| ZEC perp | -22.5% | -4 |
| LTC perp | -22.2% | -9 |
| BNB perp | -19.8% | -3 |
| LINK perp | -17.9% | -4 |
| DOT perp | -16.8% | -18 |
| NEAR perp | -9.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
