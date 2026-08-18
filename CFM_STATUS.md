# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8871** (-11.29% since start) |
| Peak / drawdown | 1.0141 / -12.53% |
| Ticks recorded | 599 |
| Last tick | 2026-08-18T04:10:24.655441+00:00 (+0.0008%) |
| Risk rails | brake: drawdown -12.5% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-18 03:00:00+00:00) |
| Gross leverage | 1.49x |
| Weeks tracked | 4 |
| Average week | -1.01% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.08% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +14.9% | +3 |
| ADA perp | +11.7% | +6 |
| XLM perp | +8.7% | +1 |
| BCH perp | +6.9% | +3 |
| BNB perp | +6.8% | +1 |
| ETH perp | +4.3% | +2 |
| SOL perp | +4.3% | +1 |
| AVAX perp | +3.5% | +5 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -23.6% | -6 |
| BTC perp | -14.4% | -2 |
| LTC perp | -12.5% | -5 |
| XRP perp | -11.2% | -2 |
| NEAR perp | -9.3% | -1 |
| DOT perp | -5.8% | -7 |
| ZEC perp | -5.7% | -1 |
| LINK perp | -5.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
