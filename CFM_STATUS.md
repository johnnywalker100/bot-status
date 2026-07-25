# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9477** (-5.23% since start) |
| Peak / drawdown | 1.0141 / -6.55% |
| Ticks recorded | 39 |
| Last tick | 2026-07-25T18:08:51.451541+00:00 (-0.9714%) |
| Risk rails | normal (dd -5.6%) |
| Data source | coinbase-cfm (bar 2026-07-25 17:00:00+00:00) |
| Gross leverage | 2.60x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +24.1% | +5 |
| ETH perp | +17.6% | +9 |
| BCH perp | +13.2% | +6 |
| ADA perp | +10.4% | +6 |
| ONDO perp | +4.0% | +1 |
| SOL perp | +3.9% | +1 |
| HBAR perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -30.6% | -8 |
| LTC perp | -24.1% | -10 |
| ZEC perp | -20.4% | -4 |
| NEAR perp | -18.8% | -2 |
| SUI perp | -18.7% | -5 |
| PEPE perp | -17.5% | -6 |
| LINK perp | -13.2% | -3 |
| HYPE perp | -12.2% | -2 |
| ENA perp | -9.1% | -2 |
| SHIB perp | -6.8% | -13 |
| BTC perp | -6.7% | -1 |
| DOT perp | -5.1% | -6 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
