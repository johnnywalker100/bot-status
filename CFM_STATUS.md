# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9431** (-5.69% since start) |
| Peak / drawdown | 1.0141 / -7.00% |
| Ticks recorded | 48 |
| Last tick | 2026-07-26T03:08:43.703969+00:00 (-0.9939%) |
| Risk rails | normal (dd -7.0%) |
| Data source | coinbase-cfm (bar 2026-07-26 02:00:00+00:00) |
| Gross leverage | 3.01x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.6% | +4 |
| ADA perp | +19.3% | +11 |
| AVAX perp | +16.4% | +23 |
| ETH perp | +11.9% | +6 |
| BCH perp | +11.1% | +5 |
| XLM perp | +9.4% | +1 |
| SOL perp | +4.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.5% | -9 |
| LTC perp | -27.3% | -11 |
| ONDO perp | -20.3% | -5 |
| NEAR perp | -19.0% | -2 |
| ZEC perp | -15.5% | -3 |
| SUI perp | -15.1% | -4 |
| PEPE perp | -15.1% | -5 |
| LINK perp | -13.4% | -3 |
| HYPE perp | -12.4% | -2 |
| ENA perp | -9.1% | -2 |
| BTC perp | -6.8% | -1 |
| BNB perp | -6.0% | -1 |
| XRP perp | -5.8% | -1 |
| HBAR perp | -3.7% | -1 |
| SHIB perp | -2.8% | -5 |
| DOT perp | -2.6% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
