# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9530** (-4.70% since start) |
| Peak / drawdown | 1.0141 / -6.02% |
| Ticks recorded | 248 |
| Last tick | 2026-08-03T11:09:14.837774+00:00 (+0.1213%) |
| Risk rails | normal (dd -6.0%) |
| Data source | coinbase-cfm (bar 2026-08-03 10:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 2 |
| Average week | +1.54% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +1.34% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.9% | +16 |
| XLM perp | +26.9% | +3 |
| SOL perp | +15.2% | +4 |
| ADA perp | +9.8% | +5 |
| AAVE perp | +4.8% | +1 |
| DOT perp | +3.4% | +4 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -37.0% | -16 |
| BNB perp | -36.9% | -6 |
| DOGE perp | -32.7% | -9 |
| BCH perp | -24.3% | -11 |
| ZEC perp | -20.1% | -4 |
| LINK perp | -17.2% | -4 |
| XRP perp | -16.8% | -3 |
| BTC perp | -13.1% | -2 |
| NEAR perp | -9.0% | -1 |
| AVAX perp | -3.4% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
