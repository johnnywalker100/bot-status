# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9429** (-5.71% since start) |
| Peak / drawdown | 1.0141 / -7.02% |
| Ticks recorded | 237 |
| Last tick | 2026-08-03T00:08:47.320751+00:00 (+0.2627%) |
| Risk rails | normal (dd -7.0%) |
| Data source | coinbase-cfm (bar 2026-08-02 23:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 2 |
| Average week | +1.00% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.26% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.7% | +3 |
| ETH perp | +15.9% | +8 |
| ADA perp | +14.0% | +7 |
| DOT perp | +11.8% | +14 |
| AAVE perp | +4.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.9% | -12 |
| BNB perp | -37.3% | -6 |
| LTC perp | -26.0% | -11 |
| BCH perp | -24.8% | -11 |
| LINK perp | -22.1% | -5 |
| ZEC perp | -20.6% | -4 |
| BTC perp | -13.4% | -2 |
| XRP perp | -11.5% | -2 |
| NEAR perp | -9.1% | -1 |
| AVAX perp | -8.3% | -12 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
