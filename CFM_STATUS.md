# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9190** (-8.10% since start) |
| Peak / drawdown | 1.0141 / -9.38% |
| Ticks recorded | 396 |
| Last tick | 2026-08-09T16:08:32.205900+00:00 (-0.2054%) |
| Risk rails | normal (dd -9.4%) |
| Data source | coinbase-cfm (bar 2026-08-09 15:00:00+00:00) |
| Gross leverage | 2.49x |
| Weeks tracked | 2 |
| Average week | -0.27% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.28% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +27.2% | +13 |
| LTC perp | +20.2% | +8 |
| AAVE perp | +15.0% | +3 |
| XLM perp | +8.9% | +1 |
| SOL perp | +8.4% | +2 |
| XRP perp | +5.7% | +1 |
| ADA perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.0% | -13 |
| BCH perp | -30.9% | -13 |
| BNB perp | -19.9% | -3 |
| DOT perp | -18.5% | -21 |
| ZEC perp | -17.0% | -3 |
| LINK perp | -9.1% | -2 |
| NEAR perp | -8.9% | -1 |
| AVAX perp | -7.1% | -10 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
