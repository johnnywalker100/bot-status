# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9733** (-2.67% since start) |
| Peak / drawdown | 1.0141 / -4.03% |
| Ticks recorded | 213 |
| Last tick | 2026-08-02T00:08:45.366352+00:00 (-0.2322%) |
| Risk rails | normal (dd -4.0%) |
| Data source | coinbase-cfm (bar 2026-08-01 23:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +5.29% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.29% / +5.29% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +18.6% | +4 |
| XLM perp | +17.6% | +2 |
| ETH perp | +15.2% | +8 |
| DOT perp | +14.5% | +18 |
| ADA perp | +14.3% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.8% | -14 |
| BNB perp | -29.6% | -5 |
| LTC perp | -29.5% | -13 |
| BCH perp | -27.8% | -13 |
| ZEC perp | -23.9% | -5 |
| LINK perp | -16.6% | -4 |
| BTC perp | -12.9% | -2 |
| NEAR perp | -8.6% | -1 |
| SOL perp | -7.4% | -2 |
| AVAX perp | -6.4% | -10 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
