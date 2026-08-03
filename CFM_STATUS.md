# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9464** (-5.36% since start) |
| Peak / drawdown | 1.0141 / -6.68% |
| Ticks recorded | 251 |
| Last tick | 2026-08-03T14:11:46.344485+00:00 (-0.9331%) |
| Risk rails | normal (dd -6.7%) |
| Data source | coinbase-cfm (bar 2026-08-03 13:00:00+00:00) |
| Gross leverage | 3.07x |
| Weeks tracked | 2 |
| Average week | +1.19% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.63% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.4% | +16 |
| XLM perp | +27.3% | +3 |
| SOL perp | +15.5% | +4 |
| ADA perp | +10.3% | +5 |
| AAVE perp | +4.9% | +1 |
| DOT perp | +3.5% | +4 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -37.5% | -16 |
| BNB perp | -37.2% | -6 |
| DOGE perp | -33.4% | -9 |
| BCH perp | -24.6% | -11 |
| ZEC perp | -20.7% | -4 |
| LINK perp | -17.5% | -4 |
| XRP perp | -17.0% | -3 |
| BTC perp | -13.4% | -2 |
| NEAR perp | -9.1% | -1 |
| AVAX perp | -3.5% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
