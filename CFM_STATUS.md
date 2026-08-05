# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9155** (-8.45% since start) |
| Peak / drawdown | 1.0141 / -9.73% |
| Ticks recorded | 305 |
| Last tick | 2026-08-05T20:09:20.151243+00:00 (+0.1316%) |
| Risk rails | normal (dd -9.7%) |
| Data source | coinbase-cfm (bar 2026-08-05 19:00:00+00:00) |
| Gross leverage | 3.07x |
| Weeks tracked | 2 |
| Average week | -0.46% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.65% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.5% | +16 |
| XLM perp | +27.4% | +3 |
| AAVE perp | +19.6% | +4 |
| ADA perp | +14.5% | +7 |
| SOL perp | +12.2% | +3 |
| BTC perp | +7.1% | +1 |
| AVAX perp | +5.1% | +7 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.5% | -9 |
| BCH perp | -23.5% | -10 |
| XRP perp | -23.3% | -4 |
| ZEC perp | -22.6% | -4 |
| LTC perp | -22.2% | -9 |
| BNB perp | -19.6% | -3 |
| LINK perp | -17.9% | -4 |
| DOT perp | -14.8% | -16 |
| NEAR perp | -9.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
