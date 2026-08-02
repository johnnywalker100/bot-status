# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9548** (-4.52% since start) |
| Peak / drawdown | 1.0141 / -5.85% |
| Ticks recorded | 222 |
| Last tick | 2026-08-02T09:08:19.596821+00:00 (+0.4338%) |
| Risk rails | normal (dd -5.8%) |
| Data source | coinbase-cfm (bar 2026-08-02 08:00:00+00:00) |
| Gross leverage | 3.06x |
| Weeks tracked | 1 |
| Average week | +3.29% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.29% / +3.29% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.5% | +3 |
| ETH perp | +17.6% | +9 |
| ADA perp | +15.6% | +8 |
| DOT perp | +11.6% | +14 |
| AAVE perp | +4.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -43.9% | -12 |
| BNB perp | -42.7% | -7 |
| LTC perp | -25.7% | -11 |
| ZEC perp | -24.8% | -5 |
| BCH perp | -24.4% | -11 |
| LINK perp | -21.8% | -5 |
| BTC perp | -13.2% | -2 |
| XRP perp | -11.3% | -2 |
| NEAR perp | -9.0% | -1 |
| AVAX perp | -8.3% | -12 |
| SOL perp | -3.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
