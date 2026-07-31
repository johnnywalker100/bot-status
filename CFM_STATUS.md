# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9407** (-5.93% since start) |
| Peak / drawdown | 1.0141 / -7.24% |
| Ticks recorded | 168 |
| Last tick | 2026-07-31T02:09:15.712856+00:00 (+0.8474%) |
| Risk rails | normal (dd -7.2%) |
| Data source | coinbase-cfm (bar 2026-07-31 01:00:00+00:00) |
| Gross leverage | 3.04x |
| Weeks tracked | 1 |
| Average week | +1.76% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.76% / +1.76% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.7% | +12 |
| AAVE perp | +21.2% | +4 |
| XLM perp | +18.2% | +2 |
| DOT perp | +10.6% | +13 |
| ETH perp | +10.2% | +5 |
| SOL perp | +7.9% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.6% | -13 |
| LTC perp | -38.7% | -16 |
| BCH perp | -25.4% | -11 |
| BNB perp | -25.1% | -4 |
| ZEC perp | -19.8% | -4 |
| LINK perp | -17.9% | -4 |
| BTC perp | -13.7% | -2 |
| AVAX perp | -10.3% | -15 |
| NEAR perp | -8.9% | -1 |
| XRP perp | -5.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
