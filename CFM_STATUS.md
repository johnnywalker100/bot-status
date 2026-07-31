# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9600** (-4.00% since start) |
| Peak / drawdown | 1.0141 / -5.34% |
| Ticks recorded | 187 |
| Last tick | 2026-07-31T22:08:36.486927+00:00 (-0.1284%) |
| Risk rails | normal (dd -5.3%) |
| Data source | coinbase-cfm (bar 2026-07-31 21:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +3.85% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.85% / +3.85% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.0% | +12 |
| AAVE perp | +19.6% | +4 |
| XLM perp | +18.0% | +2 |
| DOT perp | +11.1% | +14 |
| ETH perp | +9.7% | +5 |
| SOL perp | +7.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.8% | -14 |
| LTC perp | -39.5% | -17 |
| BNB perp | -24.5% | -4 |
| BCH perp | -24.0% | -11 |
| ZEC perp | -19.0% | -4 |
| LINK perp | -17.0% | -4 |
| BTC perp | -13.1% | -2 |
| AVAX perp | -9.3% | -14 |
| NEAR perp | -8.7% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
