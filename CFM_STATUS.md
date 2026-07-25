# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9535** (-4.65% since start) |
| Peak / drawdown | 1.0141 / -5.98% |
| Ticks recorded | 43 |
| Last tick | 2026-07-25T22:08:47.642947+00:00 (-0.3815%) |
| Risk rails | normal (dd -6.0%) |
| Data source | coinbase-cfm (bar 2026-07-25 21:00:00+00:00) |
| Gross leverage | 2.62x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.9% | +5 |
| ETH perp | +17.7% | +9 |
| BCH perp | +13.2% | +6 |
| ADA perp | +10.4% | +6 |
| ONDO perp | +4.0% | +1 |
| SOL perp | +3.9% | +1 |
| HBAR perp | +3.7% | +1 |
| AVAX perp | +0.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.1% | -9 |
| LTC perp | -24.4% | -10 |
| ZEC perp | -20.3% | -4 |
| NEAR perp | -18.9% | -2 |
| SUI perp | -18.7% | -5 |
| PEPE perp | -17.3% | -6 |
| LINK perp | -13.2% | -3 |
| HYPE perp | -12.2% | -2 |
| ENA perp | -9.0% | -2 |
| BTC perp | -6.7% | -1 |
| SHIB perp | -5.7% | -11 |
| DOT perp | -4.3% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
