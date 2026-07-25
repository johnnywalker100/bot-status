# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **1.0043** (+0.43% since start) |
| Peak / drawdown | 1.0141 / -0.97% |
| Ticks recorded | 34 |
| Last tick | 2026-07-25T10:08:45.304331+00:00 (-0.3310%) |
| Risk rails | normal (dd -0.6%) |
| Data source | coinbase-cfm (bar 2026-07-25 09:00:00+00:00) |
| Gross leverage | 2.65x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +22.5% | +5 |
| ETH perp | +16.6% | +9 |
| BCH perp | +12.5% | +6 |
| ADA perp | +11.3% | +7 |
| HBAR perp | +6.9% | +2 |
| ONDO perp | +3.7% | +1 |
| SOL perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.4% | -10 |
| LTC perp | -22.7% | -10 |
| ZEC perp | -18.9% | -4 |
| PEPE perp | -18.6% | -7 |
| NEAR perp | -17.7% | -2 |
| SUI perp | -17.5% | -5 |
| SHIB perp | -14.7% | -35 |
| LINK perp | -12.3% | -3 |
| HYPE perp | -11.4% | -2 |
| ENA perp | -8.5% | -2 |
| BTC perp | -6.3% | -1 |
| DOT perp | -4.0% | -5 |
| AVAX perp | -0.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
