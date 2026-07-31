# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9586** (-4.14% since start) |
| Peak / drawdown | 1.0141 / -5.48% |
| Ticks recorded | 184 |
| Last tick | 2026-07-31T18:08:43.473697+00:00 (-0.8241%) |
| Risk rails | normal (dd -5.5%) |
| Data source | coinbase-cfm (bar 2026-07-31 17:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 1 |
| Average week | +3.70% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.70% / +3.70% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.5% | +12 |
| AAVE perp | +20.2% | +4 |
| XLM perp | +18.0% | +2 |
| DOT perp | +11.2% | +14 |
| ETH perp | +9.8% | +5 |
| SOL perp | +7.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.2% | -14 |
| LTC perp | -39.8% | -17 |
| BNB perp | -24.6% | -4 |
| BCH perp | -24.0% | -11 |
| ZEC perp | -19.3% | -4 |
| LINK perp | -17.1% | -4 |
| BTC perp | -13.2% | -2 |
| AVAX perp | -9.4% | -14 |
| NEAR perp | -8.9% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
