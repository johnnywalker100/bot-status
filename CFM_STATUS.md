# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9170** (-8.30% since start) |
| Peak / drawdown | 1.0141 / -9.58% |
| Ticks recorded | 284 |
| Last tick | 2026-08-04T23:08:48.528285+00:00 (-0.5523%) |
| Risk rails | normal (dd -9.6%) |
| Data source | coinbase-cfm (bar 2026-08-04 22:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 2 |
| Average week | -0.38% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.49% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.7% | +15 |
| XLM perp | +18.5% | +2 |
| AAVE perp | +14.8% | +3 |
| SOL perp | +12.1% | +3 |
| ADA perp | +8.4% | +4 |
| AVAX perp | +5.9% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -38.9% | -6 |
| LTC perp | -34.3% | -14 |
| DOGE perp | -30.7% | -8 |
| ZEC perp | -22.1% | -4 |
| BCH perp | -21.0% | -9 |
| BTC perp | -14.0% | -2 |
| LINK perp | -13.4% | -3 |
| DOT perp | -12.2% | -13 |
| XRP perp | -11.7% | -2 |
| NEAR perp | -9.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
