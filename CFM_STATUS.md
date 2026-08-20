# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8470** (-15.30% since start) |
| Peak / drawdown | 1.0141 / -16.48% |
| Ticks recorded | 650 |
| Last tick | 2026-08-20T07:10:27.359020+00:00 (+0.0073%) |
| Risk rails | brake: drawdown -16.5% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-20 06:00:00+00:00) |
| Gross leverage | 1.58x |
| Weeks tracked | 4 |
| Average week | -2.10% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -7.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +22.8% | +4 |
| AVAX perp | +10.4% | +13 |
| XLM perp | +10.0% | +1 |
| ADA perp | +8.7% | +4 |
| BCH perp | +7.6% | +3 |
| BNB perp | +7.4% | +1 |
| ETH perp | +5.3% | +2 |
| SOL perp | +5.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -22.2% | -5 |
| NEAR perp | -20.6% | -2 |
| LTC perp | -16.6% | -6 |
| BTC perp | -8.3% | -1 |
| XRP perp | -6.6% | -1 |
| LINK perp | -6.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
