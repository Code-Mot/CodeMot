# AI Quantitative Trading System

An AI-driven quantitative trading framework designed for multi-asset markets, including cryptocurrencies, equities, ETFs, and forex.  
The system integrates data ingestion, strategy modeling, backtesting, risk management, and automated execution.

## Overview

AI Quantitative Trading combines machine learning models with systematic trading rules to identify market opportunities, manage risk, and execute trades without emotional bias.

This project focuses on:
- Reproducible research
- Modular strategy design
- Transparent backtesting
- Extensible AI models

## Core Architecture

Data Layer
- Market data (OHLCV, order book)
- Fundamental & macro data (optional)
- Feature engineering pipeline

Strategy Layer
- Rule-based strategies
- Machine learning models
- Hybrid AI + quantitative logic

Execution Layer
- Signal generation
- Position sizing
- Order routing (paper / live)

Risk Management
- Stop-loss / take-profit
- Max drawdown control
- Exposure limits

Monitoring
- Performance metrics
- Logs & alerts
- Strategy diagnostics

## AI Models Supported

- Linear / Logistic Regression
- Random Forest
- XGBoost / LightGBM
- LSTM / GRU (time series)
- Reinforcement Learning (PPO / DQN – experimental)

Models are trained on historical data and evaluated using walk-forward validation to reduce overfitting.

## Backtesting Framework

- Vectorized backtesting
- Transaction cost simulation
- Slippage modeling
- Sharpe, Sortino, Max Drawdown
- Equity curve visualization

## Risk Disclaimer

This project is for research and educational purposes only.  
It does not constitute financial advice.  
Trading involves risk, and past performance does not guarantee future results.

## License

MIT License
