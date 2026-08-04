# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9236** (-7.64% since start) |
| Peak / drawdown | 1.0141 / -8.92% |
| Ticks recorded | 281 |
| Last tick | 2026-08-04T20:11:21.745535+00:00 (+0.2531%) |
| Risk rails | normal (dd -8.9%) |
| Data source | coinbase-cfm (bar 2026-08-04 19:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 2 |
| Average week | -0.02% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.78% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.4% | +15 |
| XLM perp | +18.4% | +2 |
| SOL perp | +16.0% | +4 |
| AAVE perp | +14.7% | +3 |
| ADA perp | +8.4% | +4 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -38.6% | -6 |
| LTC perp | -36.2% | -15 |
| DOGE perp | -30.5% | -8 |
| ZEC perp | -21.8% | -4 |
| BCH perp | -20.8% | -9 |
| BTC perp | -13.9% | -2 |
| LINK perp | -13.3% | -3 |
| DOT perp | -12.8% | -14 |
| XRP perp | -11.7% | -2 |
| NEAR perp | -9.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
