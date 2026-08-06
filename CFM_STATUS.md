# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9171** (-8.29% since start) |
| Peak / drawdown | 1.0141 / -9.56% |
| Ticks recorded | 318 |
| Last tick | 2026-08-06T09:08:23.682947+00:00 (+0.4443%) |
| Risk rails | normal (dd -9.6%) |
| Data source | coinbase-cfm (bar 2026-08-06 08:00:00+00:00) |
| Gross leverage | 2.82x |
| Weeks tracked | 2 |
| Average week | -0.37% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.48% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +35.4% | +17 |
| XLM perp | +26.5% | +3 |
| AAVE perp | +19.2% | +4 |
| ADA perp | +10.3% | +5 |
| SOL perp | +8.0% | +2 |
| LTC perp | +7.4% | +3 |
| BTC perp | +7.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.0% | -10 |
| BCH perp | -37.2% | -16 |
| ZEC perp | -22.0% | -4 |
| BNB perp | -19.4% | -3 |
| NEAR perp | -18.6% | -2 |
| DOT perp | -14.5% | -16 |
| XRP perp | -11.5% | -2 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.2% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
