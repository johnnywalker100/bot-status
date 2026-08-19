# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8636** (-13.64% since start) |
| Peak / drawdown | 1.0141 / -14.84% |
| Ticks recorded | 636 |
| Last tick | 2026-08-19T17:10:16.953537+00:00 (+0.0563%) |
| Risk rails | brake: drawdown -14.8% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-19 16:00:00+00:00) |
| Gross leverage | 1.52x |
| Weeks tracked | 4 |
| Average week | -1.65% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -5.64% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +10.7% | +2 |
| XLM perp | +9.6% | +1 |
| ADA perp | +8.3% | +4 |
| BCH perp | +7.2% | +3 |
| BNB perp | +7.2% | +1 |
| AVAX perp | +5.3% | +7 |
| SOL perp | +4.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -25.2% | -6 |
| NEAR perp | -19.5% | -2 |
| LTC perp | -13.2% | -5 |
| XRP perp | -12.3% | -2 |
| LINK perp | -11.5% | -2 |
| BTC perp | -7.9% | -1 |
| ZEC perp | -6.4% | -1 |
| DOT perp | -2.7% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
