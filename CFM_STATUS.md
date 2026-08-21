# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8532** (-14.68% since start) |
| Peak / drawdown | 1.0141 / -15.87% |
| Ticks recorded | 670 |
| Last tick | 2026-08-21T03:09:46.293034+00:00 (-0.1618%) |
| Risk rails | brake: drawdown -15.9% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-21 02:00:00+00:00) |
| Gross leverage | 1.58x |
| Weeks tracked | 4 |
| Average week | -1.93% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -6.78% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.5% | +4 |
| SOL perp | +15.6% | +3 |
| BNB perp | +15.4% | +2 |
| XLM perp | +10.7% | +1 |
| AVAX perp | +9.3% | +11 |
| ETH perp | +8.2% | +3 |
| BCH perp | +7.9% | +3 |
| DOT perp | +7.9% | +8 |
| ADA perp | +7.2% | +3 |
| LINK perp | +6.4% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -20.8% | -2 |
| DOGE perp | -19.1% | -4 |
| LTC perp | -5.6% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
