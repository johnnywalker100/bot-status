# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9207** (-7.93% since start) |
| Peak / drawdown | 1.0141 / -9.21% |
| Ticks recorded | 285 |
| Last tick | 2026-08-05T00:08:18.286595+00:00 (+0.4101%) |
| Risk rails | normal (dd -9.2%) |
| Data source | coinbase-cfm (bar 2026-08-04 23:00:00+00:00) |
| Gross leverage | 3.06x |
| Weeks tracked | 2 |
| Average week | -0.18% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.09% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.4% | +15 |
| XLM perp | +18.2% | +2 |
| SOL perp | +16.0% | +4 |
| AAVE perp | +14.7% | +3 |
| ADA perp | +8.4% | +4 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -38.7% | -6 |
| LTC perp | -36.5% | -15 |
| DOGE perp | -34.1% | -9 |
| ZEC perp | -21.9% | -4 |
| BCH perp | -20.9% | -9 |
| BTC perp | -13.9% | -2 |
| LINK perp | -13.2% | -3 |
| DOT perp | -12.1% | -13 |
| XRP perp | -11.6% | -2 |
| NEAR perp | -9.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
