# Bitcoin Price Prediction

## Overview
This script, focuses on predicting Bitcoin prices using various machine learning techniques. It covers data preparation, basic statistics, visualization, model training, and evaluation. The goal is to provide insights into Bitcoin price movements and enhance predictive capabilities.

## Contents
- Data Preparation: Utilizes YFinance to gather Bitcoin and S&P 500 data, along with gold prices from Quandl.
- Basic Statistics: Computes rolling means and volatilities for Bitcoin, S&P 500, and gold.
- Visualization: Plots price evolution, scatter plots, and daily return histograms.
- Model Training: Implements SGDRegressor model for price prediction.
- LSTM Model: Develops an LSTM model with varying architectures to predict Bitcoin prices.
- Evaluation: Analyzes model performance, directional accuracy, and provides insights.

## Key Findings
- Linear models exhibit limitations in capturing Bitcoin price dynamics.
- LSTM models show promise, with directional accuracy up to 58.25% using a 4-layer architecture.
- Model performance varies based on parameters like epochs, layers, and lookback periods.
- Continuous model refinement and optimization are crucial for accurate predictions.

## Next Steps
- Develop an interactive web interface for real-time predictions.
- Incorporate live data feeds for up-to-date insights.
- Fine-tune model parameters and explore additional features for enhanced performance.
- Integrate external data sources and conduct correlation analysis with other cryptocurrencies.
- Deploy the model in a production environment and establish monitoring mechanisms.

## Conclusion
The script provides a comprehensive analysis of Bitcoin price prediction, highlighting the importance of continuous model evaluation and optimization. By implementing the suggested next steps, the model can be further refined to make more accurate predictions in the dynamic cryptocurrency market.