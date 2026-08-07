# ES volatility research — interactive tools

Two self-contained, interactive research illustrations from the **order-flow-volatility** project
(Hull Tactical, futures feature research). Open in any browser — no install, no server.

## Live site

- **Position sizing with a volatility forecast** — https://coreyzhang76.github.io/es-position-sizing/
- **Short-term volatility forecaster** — https://coreyzhang76.github.io/es-position-sizing/forecaster.html

## What they show

- *Sizing:* one S&P 500 futures signal sized two ways at the same average risk (fixed vs
  volatility-targeted), on 16 years of ES daily data. The honest result: vol-targeting is risk
  control — steadier volatility and smaller drawdowns at about the same Sharpe — not extra return.
- *Forecaster:* a transparent surrogate of the short-horizon ES volatility forecaster; drive the
  order-flow inputs by hand or replay recorded sessions.

## Code, methodology & findings

The models, tests, and full write-up live in the project repository:
**https://github.com/CoreyZhang76/order-flow-volatility** (see `FINDINGS.md`).

These pages are research illustrations, not live trading advice. The embedded data is derived
daily returns and a volatility estimate; no proprietary signals are included.
