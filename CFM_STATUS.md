# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9610** (-3.90% since start) |
| Peak / drawdown | 1.0141 / -5.24% |
| Ticks recorded | 188 |
| Last tick | 2026-07-31T23:08:33.752425+00:00 (+0.1066%) |
| Risk rails | normal (dd -5.2%) |
| Data source | coinbase-cfm (bar 2026-07-31 22:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +3.96% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.96% / +3.96% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.0% | +12 |
| AAVE perp | +19.5% | +4 |
| XLM perp | +17.9% | +2 |
| DOT perp | +11.1% | +14 |
| ETH perp | +9.7% | +5 |
| SOL perp | +7.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.7% | -14 |
| LTC perp | -39.2% | -17 |
| BNB perp | -24.4% | -4 |
| BCH perp | -24.0% | -11 |
| ZEC perp | -19.0% | -4 |
| LINK perp | -17.0% | -4 |
| BTC perp | -13.1% | -2 |
| AVAX perp | -9.3% | -14 |
| NEAR perp | -8.6% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
