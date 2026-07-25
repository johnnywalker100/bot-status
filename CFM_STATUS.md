# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9509** (-4.91% since start) |
| Peak / drawdown | 1.0141 / -6.23% |
| Ticks recorded | 40 |
| Last tick | 2026-07-25T19:08:42.940537+00:00 (+0.3429%) |
| Risk rails | normal (dd -6.6%) |
| Data source | coinbase-cfm (bar 2026-07-25 18:00:00+00:00) |
| Gross leverage | 2.61x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +24.2% | +5 |
| ETH perp | +17.8% | +9 |
| BCH perp | +13.3% | +6 |
| ADA perp | +10.5% | +6 |
| ONDO perp | +4.1% | +1 |
| SOL perp | +3.9% | +1 |
| HBAR perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -30.7% | -8 |
| LTC perp | -24.4% | -10 |
| ZEC perp | -20.5% | -4 |
| NEAR perp | -19.0% | -2 |
| SUI perp | -18.9% | -5 |
| PEPE perp | -17.5% | -6 |
| LINK perp | -13.3% | -3 |
| HYPE perp | -12.3% | -2 |
| ENA perp | -9.1% | -2 |
| SHIB perp | -6.8% | -13 |
| BTC perp | -6.8% | -1 |
| DOT perp | -4.3% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
