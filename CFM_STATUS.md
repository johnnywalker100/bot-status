# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9523** (-4.77% since start) |
| Peak / drawdown | 1.0141 / -6.09% |
| Ticks recorded | 169 |
| Last tick | 2026-07-31T03:08:39.504327+00:00 (+1.2417%) |
| Risk rails | normal (dd -6.1%) |
| Data source | coinbase-cfm (bar 2026-07-31 02:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 1 |
| Average week | +3.03% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.03% / +3.03% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.4% | +12 |
| AAVE perp | +20.8% | +4 |
| XLM perp | +17.9% | +2 |
| DOT perp | +11.2% | +14 |
| ETH perp | +10.0% | +5 |
| SOL perp | +7.8% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.8% | -13 |
| LTC perp | -38.0% | -16 |
| BCH perp | -24.7% | -11 |
| BNB perp | -24.7% | -4 |
| ZEC perp | -19.3% | -4 |
| LINK perp | -17.5% | -4 |
| BTC perp | -13.5% | -2 |
| AVAX perp | -10.1% | -15 |
| NEAR perp | -8.6% | -1 |
| XRP perp | -5.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
