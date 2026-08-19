# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8808** (-11.92% since start) |
| Peak / drawdown | 1.0141 / -13.14% |
| Ticks recorded | 630 |
| Last tick | 2026-08-19T11:10:23.986564+00:00 (-0.1887%) |
| Risk rails | brake: drawdown -13.1% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-19 10:00:00+00:00) |
| Gross leverage | 1.53x |
| Weeks tracked | 4 |
| Average week | -1.18% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.76% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +10.0% | +2 |
| XLM perp | +8.9% | +1 |
| ADA perp | +7.9% | +4 |
| BCH perp | +6.9% | +3 |
| BNB perp | +6.8% | +1 |
| AVAX perp | +5.8% | +8 |
| SOL perp | +4.4% | +1 |
| ETH perp | +2.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -23.9% | -6 |
| NEAR perp | -18.3% | -2 |
| BTC perp | -14.6% | -2 |
| LTC perp | -12.7% | -5 |
| XRP perp | -11.4% | -2 |
| LINK perp | -11.1% | -2 |
| ZEC perp | -5.8% | -1 |
| DOT perp | -1.8% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
