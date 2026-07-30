# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9516** (-4.84% since start) |
| Peak / drawdown | 1.0141 / -6.17% |
| Ticks recorded | 150 |
| Last tick | 2026-07-30T08:08:55.620791+00:00 (+0.9081%) |
| Risk rails | normal (dd -6.2%) |
| Data source | coinbase-cfm (bar 2026-07-30 07:00:00+00:00) |
| Gross leverage | 3.10x |
| Weeks tracked | 1 |
| Average week | +2.95% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.95% / +2.95% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.3% | +13 |
| AAVE perp | +20.3% | +4 |
| ETH perp | +16.0% | +8 |
| DOT perp | +13.7% | +17 |
| XLM perp | +9.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.0% | -12 |
| LTC perp | -40.4% | -17 |
| BNB perp | -30.2% | -5 |
| NEAR perp | -25.6% | -3 |
| ZEC perp | -24.9% | -5 |
| BTC perp | -20.2% | -3 |
| LINK perp | -17.4% | -4 |
| BCH perp | -8.8% | -4 |
| AVAX perp | -7.4% | -11 |
| XRP perp | -5.7% | -1 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
