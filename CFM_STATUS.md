# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9367** (-6.33% since start) |
| Peak / drawdown | 1.0141 / -7.64% |
| Ticks recorded | 92 |
| Last tick | 2026-07-27T23:08:47.111602+00:00 (+0.8861%) |
| Risk rails | normal (dd -7.6%) |
| Data source | coinbase-cfm (bar 2026-07-27 22:00:00+00:00) |
| Gross leverage | 2.85x |
| Weeks tracked | 1 |
| Average week | +1.33% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.33% / +1.33% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.0% | +5 |
| ADA perp | +24.8% | +15 |
| XLM perp | +18.3% | +2 |
| BCH perp | +18.0% | +8 |
| ETH perp | +10.1% | +5 |
| DOT perp | +4.8% | +6 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -52.5% | -14 |
| LTC perp | -34.3% | -14 |
| LINK perp | -22.4% | -5 |
| BTC perp | -20.4% | -3 |
| BNB perp | -18.1% | -3 |
| ZEC perp | -15.3% | -3 |
| XRP perp | -11.4% | -2 |
| NEAR perp | -9.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
