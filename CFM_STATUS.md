# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9067** (-9.33% since start) |
| Peak / drawdown | 1.0141 / -10.59% |
| Ticks recorded | 454 |
| Last tick | 2026-08-12T02:08:37.941504+00:00 (+0.1725%) |
| Risk rails | normal (dd -10.6%) |
| Data source | coinbase-cfm (bar 2026-08-12 01:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | -0.63% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.37% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.2% | +16 |
| AAVE perp | +24.6% | +5 |
| LTC perp | +20.0% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -40.1% | -17 |
| DOGE perp | -35.9% | -9 |
| BTC perp | -35.2% | -5 |
| ADA perp | -20.6% | -10 |
| BNB perp | -20.5% | -3 |
| DOT perp | -20.1% | -23 |
| ZEC perp | -15.9% | -3 |
| LINK perp | -14.5% | -3 |
| NEAR perp | -9.1% | -1 |
| XLM perp | -9.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
