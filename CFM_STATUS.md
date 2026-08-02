# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9534** (-4.66% since start) |
| Peak / drawdown | 1.0141 / -5.99% |
| Ticks recorded | 219 |
| Last tick | 2026-08-02T06:08:50.280011+00:00 (+0.1732%) |
| Risk rails | normal (dd -6.0%) |
| Data source | coinbase-cfm (bar 2026-08-02 05:00:00+00:00) |
| Gross leverage | 3.06x |
| Weeks tracked | 1 |
| Average week | +3.14% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.14% / +3.14% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.8% | +3 |
| ETH perp | +15.7% | +8 |
| ADA perp | +15.5% | +8 |
| DOT perp | +11.6% | +14 |
| AAVE perp | +4.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.2% | -12 |
| BNB perp | -42.9% | -7 |
| LTC perp | -25.8% | -11 |
| ZEC perp | -24.8% | -5 |
| BCH perp | -24.3% | -11 |
| LINK perp | -21.9% | -5 |
| BTC perp | -13.3% | -2 |
| XRP perp | -11.4% | -2 |
| NEAR perp | -9.0% | -1 |
| AVAX perp | -9.0% | -13 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
