# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9257** (-7.43% since start) |
| Peak / drawdown | 1.0141 / -8.71% |
| Ticks recorded | 392 |
| Last tick | 2026-08-09T12:08:49.573066+00:00 (+0.3090%) |
| Risk rails | normal (dd -8.7%) |
| Data source | coinbase-cfm (bar 2026-08-09 11:00:00+00:00) |
| Gross leverage | 2.51x |
| Weeks tracked | 2 |
| Average week | +0.09% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.56% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +26.9% | +13 |
| LTC perp | +20.0% | +8 |
| AAVE perp | +19.7% | +4 |
| XLM perp | +8.8% | +1 |
| SOL perp | +8.3% | +2 |
| XRP perp | +5.6% | +1 |
| ADA perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.2% | -13 |
| BCH perp | -30.4% | -13 |
| BNB perp | -19.6% | -3 |
| DOT perp | -18.3% | -21 |
| ZEC perp | -16.9% | -3 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -7.7% | -11 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
