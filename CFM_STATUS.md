# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9523** (-4.77% since start) |
| Peak / drawdown | 1.0141 / -6.10% |
| Ticks recorded | 142 |
| Last tick | 2026-07-30T00:08:26.501202+00:00 (-0.8146%) |
| Risk rails | normal (dd -6.1%) |
| Data source | coinbase-cfm (bar 2026-07-29 23:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +3.02% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.02% / +3.02% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.1% | +4 |
| ADA perp | +18.7% | +11 |
| XLM perp | +18.1% | +2 |
| BCH perp | +13.3% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +9.6% | +12 |
| SOL perp | +3.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.9% | -13 |
| LTC perp | -38.1% | -16 |
| BNB perp | -30.0% | -5 |
| NEAR perp | -25.5% | -3 |
| BTC perp | -20.1% | -3 |
| LINK perp | -17.5% | -4 |
| ZEC perp | -14.7% | -3 |
| AVAX perp | -8.8% | -13 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
