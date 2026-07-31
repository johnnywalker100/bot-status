# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9587** (-4.13% since start) |
| Peak / drawdown | 1.0141 / -5.46% |
| Ticks recorded | 177 |
| Last tick | 2026-07-31T11:08:38.416506+00:00 (-0.5894%) |
| Risk rails | normal (dd -5.5%) |
| Data source | coinbase-cfm (bar 2026-07-31 10:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 1 |
| Average week | +3.72% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.72% / +3.72% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.3% | +12 |
| AAVE perp | +20.4% | +4 |
| XLM perp | +17.7% | +2 |
| DOT perp | +11.1% | +14 |
| ETH perp | +9.8% | +5 |
| SOL perp | +7.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.8% | -14 |
| LTC perp | -39.9% | -17 |
| BNB perp | -24.7% | -4 |
| BCH perp | -23.8% | -11 |
| ZEC perp | -19.2% | -4 |
| LINK perp | -17.2% | -4 |
| BTC perp | -13.3% | -2 |
| AVAX perp | -10.2% | -15 |
| NEAR perp | -8.6% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
