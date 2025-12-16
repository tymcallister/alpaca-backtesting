# Alpaca Backtesting

This repository contains a clean, production-ready backtesting workflow for a
VWAP reclaim strategy on SPY and QQQ using Alpaca data.

## Main Notebook
- `vwap_reclaim_spy_qqq_clean.ipynb`

## Features
- Premarket VWAP (from 4:00am CT)
- VWAP reclaim entries (6:00–7:00am CT)
- Signal-only backtest logic
- Shared portfolio accounting
- Dynamic position sizing (capped at 1.25x)
- Daily max loss as % of equity
- SPY + QQQ combined portfolio

## Status
Ready for paper trading.
