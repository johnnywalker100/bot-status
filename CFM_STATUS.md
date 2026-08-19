# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8871** (-11.29% since start) |
| Peak / drawdown | 1.0141 / -12.52% |
| Ticks recorded | 621 |
| Last tick | 2026-08-19T02:10:47.804864+00:00 (+0.0174%) |
| Risk rails | brake: drawdown -12.5% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-19 01:00:00+00:00) |
| Gross leverage | 1.50x |
| Weeks tracked | 4 |
| Average week | -1.01% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.07% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +9.8% | +2 |
| XLM perp | +8.7% | +1 |
| ADA perp | +7.8% | +4 |
| BCH perp | +6.9% | +3 |
| BNB perp | +6.8% | +1 |
| AVAX perp | +5.7% | +8 |
| SOL perp | +4.3% | +1 |
| ETH perp | +2.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -23.6% | -6 |
| NEAR perp | -17.9% | -2 |
| BTC perp | -14.5% | -2 |
| LTC perp | -12.5% | -5 |
| XRP perp | -11.2% | -2 |
| LINK perp | -10.7% | -2 |
| ZEC perp | -5.7% | -1 |
| DOT perp | -1.7% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
