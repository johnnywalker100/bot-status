# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8499** (-15.01% since start) |
| Peak / drawdown | 1.0141 / -16.19% |
| Ticks recorded | 653 |
| Last tick | 2026-08-20T10:09:27.408488+00:00 (+0.0053%) |
| Risk rails | brake: drawdown -16.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-20 09:00:00+00:00) |
| Gross leverage | 1.57x |
| Weeks tracked | 4 |
| Average week | -2.02% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -7.14% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +22.9% | +4 |
| AVAX perp | +10.6% | +13 |
| XLM perp | +10.5% | +1 |
| ADA perp | +9.0% | +4 |
| BCH perp | +7.7% | +3 |
| BNB perp | +7.6% | +1 |
| ETH perp | +5.4% | +2 |
| SOL perp | +5.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -20.8% | -2 |
| DOGE perp | -18.1% | -4 |
| LTC perp | -16.7% | -6 |
| BTC perp | -8.5% | -1 |
| XRP perp | -6.8% | -1 |
| LINK perp | -6.2% | -1 |
| DOT perp | -0.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
