# Systematic Trading Strategies — Mateo Sandoval

A library of original trading systems written in Pine Script v6 and backtested in TradingView's
Strategy Tester with commissions and slippage modeled. Every page documents the mechanism, the
parameters, the results against buy-and-hold and the S&P 500 — and the experiments that failed.

**Live site:** https://mateosandoval10.github.io/quant-strategies/

| System | Market | Headline |
|---|---|---|
| Vol-Target Trend Engine | TQQQ daily | +3,862% (2010–2026), PF 3.33, regime gate + vol targeting |
| Compression Breakout System | AAPL daily | +899% (2005–2026), PF 4.33, 14.4% max DD, risk-sized |
| Channel Reversion System | QQQ daily | PF 2.28, 64% win rate, 15% max DD, ~80% in cash |
| QV Signal Pro v2 | TQQQ daily | +489%, rebuilt from a trade-by-trade loss autopsy (full log) |

All results are in-sample, single-history backtests — treated as upper bounds, not forecasts.
Not investment advice.
