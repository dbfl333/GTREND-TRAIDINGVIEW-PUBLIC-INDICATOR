# Changelog

All notable changes to the **GTREND** TradingView indicator will be documented in this file.

## [v1.1.0] - 2026-07-05
### Added
- **Pine Script v6 Support**: Upgraded the script compiler directive to `//@version=6` to comply with TradingView's new mandatory requirements for public script publishing.
- **Explicit Linewidths**: Added strict `linewidth=1` definitions to hidden plotting elements to satisfy new v6 compiler rules (`display=display.none` is now utilized for background fills).

### Changed
- **Indicator Name Revamp**: Standardized the public title and short-title across the entire script to simply **GTREND** (formerly GTREND POWER HOUSE / GTPH).
- **ATR Period Default**: Tweaked the default ATR Period setting from `99` down to `1` for highly responsive trend catching right out of the box.

## [v1.0.0] - 2026-07-04
### Added
- **Initial Release**: Successfully merged the legacy G Trend (ATR trailing stop) code with the advanced Smart Money Concepts (SMC) suite.
- **FVG & Order Blocks**: Fully integrated dynamic Fair Value Gaps and Swing Order Blocks.
- **Auto Fibonaccis**: Added automatic plotting of key Fib retracement levels (`0.236`, `0.382`, `0.5`, `0.618`, `0.786`).
- **Session Highlighting**: Added New York, London, and Asia session background highlights and volume tracking tables.
