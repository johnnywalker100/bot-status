# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9506** (-4.94% since start) |
| Peak / drawdown | 1.0141 / -6.26% |
| Ticks recorded | 143 |
| Last tick | 2026-07-30T01:09:04.613873+00:00 (-0.1689%) |
| Risk rails | normal (dd -6.2%) |
| Data source | coinbase-cfm (bar 2026-07-30 00:00:00+00:00) |
| Gross leverage | 3.10x |
| Weeks tracked | 1 |
| Average week | +2.84% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.84% / +2.84% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.3% | +13 |
| AAVE perp | +20.0% | +4 |
| ETH perp | +16.0% | +8 |
| DOT perp | +13.7% | +17 |
| XLM perp | +9.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.4% | -12 |
| LTC perp | -40.4% | -17 |
| BNB perp | -30.1% | -5 |
| NEAR perp | -25.5% | -3 |
| ZEC perp | -24.5% | -5 |
| BTC perp | -20.1% | -3 |
| LINK perp | -17.6% | -4 |
| BCH perp | -8.8% | -4 |
| AVAX perp | -8.1% | -12 |
| XRP perp | -5.6% | -1 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
