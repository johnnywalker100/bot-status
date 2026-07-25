# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **1.0029** (+0.29% since start) |
| Peak / drawdown | 1.0141 / -1.11% |
| Ticks recorded | 30 |
| Last tick | 2026-07-25T06:08:47.484774+00:00 (+0.7509%) |
| Risk rails | normal (dd -1.8%) |
| Data source | coinbase-cfm (bar 2026-07-25 05:00:00+00:00) |
| Gross leverage | 2.62x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.0% | +5 |
| ETH perp | +16.8% | +9 |
| BCH perp | +12.7% | +6 |
| ADA perp | +11.5% | +7 |
| ONDO perp | +3.8% | +1 |
| SOL perp | +3.7% | +1 |
| HBAR perp | +3.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -31.3% | -9 |
| LTC perp | -23.2% | -10 |
| ZEC perp | -19.2% | -4 |
| PEPE perp | -18.9% | -7 |
| NEAR perp | -18.0% | -2 |
| SUI perp | -17.9% | -5 |
| SHIB perp | -14.7% | -35 |
| LINK perp | -12.5% | -3 |
| HYPE perp | -11.5% | -2 |
| ENA perp | -8.8% | -2 |
| BTC perp | -6.4% | -1 |
| DOT perp | -4.1% | -5 |
| AVAX perp | -0.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
