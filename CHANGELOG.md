# Changelog

All notable changes to the **GTREND** TradingView indicator will be documented in this file.

## [2026-07-05 00:45:00]
### Security & Repository
- **Agent Traces Removed**: Completely scrubbed AI agent operating rules and configuration files from the public git history using `.git/info/exclude` to ensure a pristine open-source footprint.

## [2026-07-05 00:25:00]
### Changed
- **Indicator Name Revamp**: Standardized the public title and short-title across the entire script to simply **GTREND** to remove abbreviation clutter.

## [2026-07-05 00:23:00]
### Changed
- **ATR Period Default**: Tweaked the default ATR Period setting from `99` down to `1` for highly responsive trend catching right out of the box.

## [2026-07-05 00:20:00]
### Fixed
- **Pine Script v6 Compiler Bug**: Fixed a stubborn compiler error where `linewidth=0` was rejected by v6. Explicitly set `linewidth=1` while utilizing `display=display.none` to maintain 100% transparency for background fills.

## [2026-07-05 00:15:00]
### Added
- **Pine Script v6 Support**: Upgraded the script compiler directive to `//@version=6` to comply with TradingView's new mandatory requirements for public script publishing.

## [2026-07-04 22:30:00]
### Added
- **Initial Release**: Successfully merged the legacy G Trend (ATR trailing stop) code with the advanced Smart Money Concepts (SMC) suite.
- **FVG & Order Blocks**: Fully integrated dynamic Fair Value Gaps and Swing Order Blocks.
- **Auto Fibonaccis**: Added automatic plotting of key Fib retracement levels.
- **Session Highlighting**: Added New York, London, and Asia session background highlights and volume tracking tables.
