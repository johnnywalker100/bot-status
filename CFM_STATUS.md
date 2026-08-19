# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8806** (-11.94% since start) |
| Peak / drawdown | 1.0141 / -13.17% |
| Ticks recorded | 632 |
| Last tick | 2026-08-19T13:08:20.484527+00:00 (-0.1256%) |
| Risk rails | brake: drawdown -13.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-19 12:00:00+00:00) |
| Gross leverage | 1.53x |
| Weeks tracked | 4 |
| Average week | -1.19% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.79% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +10.2% | +2 |
| XLM perp | +8.9% | +1 |
| ADA perp | +8.0% | +4 |
| BCH perp | +7.0% | +3 |
| BNB perp | +6.9% | +1 |
| AVAX perp | +5.8% | +8 |
| SOL perp | +4.4% | +1 |
| ETH perp | +2.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -24.0% | -6 |
| NEAR perp | -18.4% | -2 |
| BTC perp | -14.7% | -2 |
| LTC perp | -12.7% | -5 |
| XRP perp | -11.5% | -2 |
| LINK perp | -11.0% | -2 |
| ZEC perp | -5.8% | -1 |
| DOT perp | -1.8% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
