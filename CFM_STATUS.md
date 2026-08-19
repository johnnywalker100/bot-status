# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8739** (-12.61% since start) |
| Peak / drawdown | 1.0141 / -13.83% |
| Ticks recorded | 634 |
| Last tick | 2026-08-19T15:08:53.360347+00:00 (-0.5001%) |
| Risk rails | brake: drawdown -13.8% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-19 14:00:00+00:00) |
| Gross leverage | 1.58x |
| Weeks tracked | 4 |
| Average week | -1.37% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -4.52% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +10.6% | +2 |
| XLM perp | +9.3% | +1 |
| ADA perp | +8.2% | +4 |
| BCH perp | +7.1% | +3 |
| BNB perp | +7.0% | +1 |
| AVAX perp | +5.9% | +8 |
| SOL perp | +4.7% | +1 |
| ETH perp | +2.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -24.7% | -6 |
| NEAR perp | -18.8% | -2 |
| BTC perp | -15.2% | -2 |
| LTC perp | -13.0% | -5 |
| XRP perp | -11.9% | -2 |
| LINK perp | -11.2% | -2 |
| ZEC perp | -6.3% | -1 |
| DOT perp | -1.8% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
