# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9558** (-4.42% since start) |
| Peak / drawdown | 1.0141 / -5.75% |
| Ticks recorded | 244 |
| Last tick | 2026-08-03T07:09:24.683167+00:00 (+0.5757%) |
| Risk rails | normal (dd -5.7%) |
| Data source | coinbase-cfm (bar 2026-08-03 06:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 2 |
| Average week | +1.69% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +1.64% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.9% | +16 |
| XLM perp | +26.8% | +3 |
| SOL perp | +15.2% | +4 |
| ADA perp | +9.6% | +5 |
| AAVE perp | +4.8% | +1 |
| DOT perp | +3.3% | +4 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -37.1% | -16 |
| BNB perp | -36.5% | -6 |
| DOGE perp | -32.6% | -9 |
| BCH perp | -24.2% | -11 |
| ZEC perp | -19.8% | -4 |
| LINK perp | -17.2% | -4 |
| XRP perp | -16.8% | -3 |
| BTC perp | -13.1% | -2 |
| NEAR perp | -8.9% | -1 |
| AVAX perp | -3.3% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
