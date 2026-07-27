# TCS-stock-prediction
TCS Stock Price Prediction: Model Benchmarking & AnalysisA comparative machine learning and deep learning framework designed to evaluate time-series forecasting models using historical stock market data for Tata Consultancy Services (TCS) sourced via Yahoo Finance (yfinance).  

🌟 Why Use This Project?
Most stock prediction repositories default to complex neural networks without validating if simpler approaches work better. This project takes an empirical, data-driven approach by systematically benchmarking baseline statistical algorithms against ensemble learning and sequential deep learning architectures on real-world Indian stock market data.  
✨ Key Highlights & Uniqueness
Honest Model Benchmarking: Instead of forcing complex architectures, this project benchmarks Linear Regression, Random Forest Regressor, and Long Short-Term Memory (LSTM) networks under identical test conditions.  
The Simplicity Advantage: Demonstrates the Bias-Variance Tradeoff in financial modeling—showing how feature engineering (moving averages, daily returns, and OHLC indicators) creates strong linear correlations where transparent regression models can outperform complex deep learning networks.  
Comprehensive Pipeline: Complete end-to-end workflow covering automated data acquisition (5+ years of daily data), exploratory trend analysis, feature scaling, and sequence generation.  
Interactive Visualization: Generates lightweight standalone HTML visual reports (tcs_prediction.html) alongside tracking graphs comparing actual vs. predicted prices over real dates.  
