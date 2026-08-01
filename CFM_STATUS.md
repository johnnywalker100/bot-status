# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9445** (-5.55% since start) |
| Peak / drawdown | 1.0141 / -6.86% |
| Ticks recorded | 194 |
| Last tick | 2026-08-01T05:08:37.660576+00:00 (-0.3654%) |
| Risk rails | normal (dd -6.9%) |
| Data source | coinbase-cfm (bar 2026-08-01 04:00:00+00:00) |
| Gross leverage | 3.09x |
| Weeks tracked | 1 |
| Average week | +2.18% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.18% / +2.18% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.5% | +4 |
| XLM perp | +18.2% | +2 |
| ETH perp | +15.8% | +8 |
| ADA perp | +14.5% | +8 |
| DOT perp | +13.8% | +17 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -52.0% | -14 |
| BNB perp | -31.3% | -5 |
| LTC perp | -30.7% | -13 |
| BCH perp | -29.1% | -13 |
| ZEC perp | -24.6% | -5 |
| LINK perp | -17.4% | -4 |
| BTC perp | -13.3% | -2 |
| NEAR perp | -8.9% | -1 |
| SOL perp | -7.7% | -2 |
| AVAX perp | -6.8% | -10 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
