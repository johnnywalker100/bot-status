# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9433** (-5.67% since start) |
| Peak / drawdown | 1.0141 / -6.98% |
| Ticks recorded | 268 |
| Last tick | 2026-08-04T07:09:07.281563+00:00 (+0.3192%) |
| Risk rails | normal (dd -7.0%) |
| Data source | coinbase-cfm (bar 2026-08-04 06:00:00+00:00) |
| Gross leverage | 3.06x |
| Weeks tracked | 2 |
| Average week | +1.02% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.30% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +29.5% | +15 |
| XLM perp | +18.1% | +2 |
| SOL perp | +15.6% | +4 |
| AAVE perp | +14.7% | +3 |
| ADA perp | +8.3% | +4 |
| AVAX perp | +5.7% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -37.5% | -6 |
| LTC perp | -35.1% | -15 |
| DOGE perp | -33.4% | -9 |
| BCH perp | -22.6% | -10 |
| ZEC perp | -20.6% | -4 |
| LINK perp | -17.3% | -4 |
| BTC perp | -13.5% | -2 |
| DOT perp | -13.2% | -15 |
| XRP perp | -11.4% | -2 |
| NEAR perp | -9.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
