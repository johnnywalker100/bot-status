# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8896** (-11.04% since start) |
| Peak / drawdown | 1.0141 / -12.27% |
| Ticks recorded | 681 |
| Last tick | 2026-08-21T14:08:36.933808+00:00 (+0.3757%) |
| Risk rails | brake: drawdown -12.3% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-21 13:00:00+00:00) |
| Gross leverage | 0.86x |
| Weeks tracked | 4 |
| Average week | -0.94% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.80% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +12.5% | +2 |
| SOL perp | +10.2% | +2 |
| BNB perp | +7.6% | +1 |
| LINK perp | +6.4% | +1 |
| BCH perp | +6.1% | +2 |
| AVAX perp | +6.0% | +7 |
| ETH perp | +5.4% | +2 |
| ADA perp | +4.9% | +2 |
| DOT perp | +4.0% | +4 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -10.6% | -1 |
| DOGE perp | -9.4% | -2 |
| LTC perp | -2.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
