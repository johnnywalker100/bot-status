# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9480** (-5.20% since start) |
| Peak / drawdown | 1.0141 / -6.52% |
| Ticks recorded | 193 |
| Last tick | 2026-08-01T04:08:58.606700+00:00 (-0.0875%) |
| Risk rails | normal (dd -6.5%) |
| Data source | coinbase-cfm (bar 2026-08-01 03:00:00+00:00) |
| Gross leverage | 3.08x |
| Weeks tracked | 1 |
| Average week | +2.56% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.56% / +2.56% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.5% | +4 |
| XLM perp | +18.1% | +2 |
| ETH perp | +15.8% | +8 |
| ADA perp | +14.4% | +8 |
| DOT perp | +13.7% | +17 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.7% | -14 |
| BNB perp | -31.1% | -5 |
| LTC perp | -30.5% | -13 |
| BCH perp | -29.0% | -13 |
| ZEC perp | -24.5% | -5 |
| LINK perp | -17.3% | -4 |
| BTC perp | -13.3% | -2 |
| NEAR perp | -8.8% | -1 |
| SOL perp | -7.7% | -2 |
| AVAX perp | -6.8% | -10 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
