# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9556** (-4.44% since start) |
| Peak / drawdown | 1.0141 / -5.77% |
| Ticks recorded | 217 |
| Last tick | 2026-08-02T04:08:59.135081+00:00 (-0.2644%) |
| Risk rails | normal (dd -5.8%) |
| Data source | coinbase-cfm (bar 2026-08-02 03:00:00+00:00) |
| Gross leverage | 3.05x |
| Weeks tracked | 1 |
| Average week | +3.38% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.38% / +3.38% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.3% | +3 |
| ETH perp | +15.7% | +8 |
| ADA perp | +15.1% | +8 |
| DOT perp | +11.6% | +14 |
| AAVE perp | +4.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.0% | -12 |
| BNB perp | -42.8% | -7 |
| LTC perp | -25.7% | -11 |
| ZEC perp | -24.7% | -5 |
| BCH perp | -24.1% | -11 |
| LINK perp | -21.7% | -5 |
| BTC perp | -13.3% | -2 |
| XRP perp | -11.3% | -2 |
| AVAX perp | -9.9% | -15 |
| NEAR perp | -9.0% | -1 |
| SOL perp | -3.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
