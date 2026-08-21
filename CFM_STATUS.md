# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8971** (-10.29% since start) |
| Peak / drawdown | 1.0141 / -11.54% |
| Ticks recorded | 688 |
| Last tick | 2026-08-21T22:10:25.381581+00:00 (+1.6069%) |
| Risk rails | normal (dd -11.5%); blind 2.0h -> 50% size on resume |
| Data source | coinbase-cfm (bar 2026-08-21 21:00:00+00:00) |
| Gross leverage | 0.90x |
| Weeks tracked | 4 |
| Average week | -0.74% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.99% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +13.5% | +2 |
| SOL perp | +10.5% | +2 |
| BNB perp | +7.7% | +1 |
| LINK perp | +6.9% | +1 |
| BCH perp | +6.6% | +2 |
| AVAX perp | +6.1% | +7 |
| ETH perp | +5.7% | +2 |
| ADA perp | +5.1% | +2 |
| DOT perp | +4.2% | +4 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -11.0% | -1 |
| DOGE perp | -10.4% | -2 |
| LTC perp | -3.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
