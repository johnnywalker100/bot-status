# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9670** (-3.30% since start) |
| Peak / drawdown | 1.0141 / -4.65% |
| Ticks recorded | 130 |
| Last tick | 2026-07-29T12:08:59.549384+00:00 (+0.0575%) |
| Risk rails | normal (dd -4.6%) |
| Data source | coinbase-cfm (bar 2026-07-29 11:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +4.61% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.61% / +4.61% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.2% | +4 |
| ADA perp | +18.6% | +11 |
| XLM perp | +18.0% | +2 |
| BCH perp | +13.2% | +6 |
| ETH perp | +9.9% | +5 |
| DOT perp | +9.4% | +12 |
| SOL perp | +3.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.4% | -13 |
| LTC perp | -37.4% | -16 |
| BNB perp | -29.5% | -5 |
| NEAR perp | -24.6% | -3 |
| BTC perp | -20.0% | -3 |
| LINK perp | -17.3% | -4 |
| ZEC perp | -14.2% | -3 |
| AVAX perp | -8.6% | -13 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
