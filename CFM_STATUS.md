# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8508** (-14.92% since start) |
| Peak / drawdown | 1.0141 / -16.10% |
| Ticks recorded | 656 |
| Last tick | 2026-08-20T13:10:50.164795+00:00 (-0.0329%) |
| Risk rails | brake: drawdown -16.1% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-20 12:00:00+00:00) |
| Gross leverage | 1.57x |
| Weeks tracked | 4 |
| Average week | -2.00% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -7.04% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +22.8% | +4 |
| XLM perp | +10.7% | +1 |
| AVAX perp | +10.5% | +13 |
| ADA perp | +9.0% | +4 |
| BCH perp | +7.6% | +3 |
| BNB perp | +7.6% | +1 |
| ETH perp | +5.4% | +2 |
| SOL perp | +5.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -20.3% | -2 |
| DOGE perp | -18.2% | -4 |
| LTC perp | -16.7% | -6 |
| BTC perp | -8.5% | -1 |
| XRP perp | -7.0% | -1 |
| LINK perp | -6.2% | -1 |
| DOT perp | -1.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
