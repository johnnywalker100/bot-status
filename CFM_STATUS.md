# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9484** (-5.16% since start) |
| Peak / drawdown | 1.0141 / -6.48% |
| Ticks recorded | 172 |
| Last tick | 2026-07-31T06:08:52.480176+00:00 (+0.1014%) |
| Risk rails | normal (dd -6.5%) |
| Data source | coinbase-cfm (bar 2026-07-31 05:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 1 |
| Average week | +2.60% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.60% / +2.60% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.3% | +12 |
| AAVE perp | +21.1% | +4 |
| XLM perp | +18.0% | +2 |
| DOT perp | +10.5% | +13 |
| ETH perp | +10.0% | +5 |
| SOL perp | +3.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.1% | -13 |
| LTC perp | -38.2% | -16 |
| BNB perp | -24.9% | -4 |
| BCH perp | -24.8% | -11 |
| ZEC perp | -19.5% | -4 |
| LINK perp | -17.6% | -4 |
| BTC perp | -13.6% | -2 |
| AVAX perp | -10.2% | -15 |
| NEAR perp | -8.7% | -1 |
| XRP perp | -5.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
