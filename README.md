
# BSE_stock_predictor

## BSE SENSEX Stock Price Prediction Model

![BSE SENSEX](https://img.shields.io/badge/Market-BSE%20SENSEX-blue)
![Python](https://img.shields.io/badge/Python-3.8+-brightgreen)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange)
![NLTK](https://img.shields.io/badge/NLTK-3.6+-yellow)

## 📊 Overview
This project implements an advanced machine learning system to predict BSE SENSEX index movements by combining technical analysis with natural language processing of news sentiment. The hybrid approach integrates traditional stock indicators with deep learning to achieve accurate forecasting results.

## 🚀 Key Achievements
- **Linear Regression Model:**
  - MAE: 323.21
  - RMSE: 484.72
  - R²: 0.9805
- **LSTM Model:**
  - MAE: 2861.64
  - RMSE: 3276.44
  - R²: 0.1100
- **Ensemble Model:**
  - MAE: 920.70
  - RMSE: 1092.83
  - R²: 0.9010
- Successfully integrated sentiment analysis from news headlines into stock price prediction.
- Engineered comprehensive technical indicators for enhanced prediction accuracy.

## ✨ Features
- **Data Integration:** Merged BSE SENSEX historical data (2001-2020) with Indian news headlines.
- **Sentiment Analysis:** Enhanced VADER sentiment analysis with a custom financial lexicon.
- **Feature Engineering:** Implemented technical indicators including:
  - Moving Averages (SMA, EMA)
  - Relative Strength Index (RSI)
  - Bollinger Bands
  - MACD (Moving Average Convergence Divergence)
  - Volume analysis
- **Hybrid Model Architecture:** Combined linear regression for baseline predictions with LSTM networks for complex pattern recognition.
- **Performance Evaluation:** Comprehensive metrics suite including RMSE, MAE, and R².

## 🛠️ Technologies Used
- **Python:** Core programming language
- **Pandas & NumPy:** Data manipulation and processing
- **yfinance:** Financial data acquisition
- **NLTK:** Natural language processing for sentiment analysis
- **Scikit-learn:** Machine learning algorithms and evaluation
- **TensorFlow/Keras:** Deep learning model implementation
- **Matplotlib:** Data visualization

## 📊 Dataset Information
This project utilizes two primary datasets:

1. **BSE SENSEX Historical Data (2001-2020):**
    - Daily price data including Open, High, Low, Close, and Volume.
    - Downloaded using yfinance API.

2. **Times of India News Headlines Dataset:**
    - Contains approximately 3.4 million news events.
    - Comprehensive coverage of Indian events from 2001-2020.
    - Provides rich sentiment data for financial market analysis.

## 📝 Methodology

### Data Preprocessing:
- Cleaning and normalizing both datasets.
- Aligning news headlines with trading days.
- Feature scaling and normalization.

### Sentiment Analysis:
- Enhanced VADER sentiment analyzer with financial lexicon.
- Sentiment scoring and normalization.

### Feature Engineering:
- Creating technical indicators.
- Developing sentiment features.

### Model Development:
- Linear Regression baseline model.
- LSTM neural network implementation.
- Hyperparameter tuning.

### Evaluation and Validation:
- Performance metrics calculation.
- Model comparison and ensemble techniques.

## 📈 Results
The hybrid model demonstrates improvements in prediction accuracy through the integration of sentiment analysis and technical indicators:
- Linear Regression Model: **R²: 0.9805**
- LSTM Model: **R²: 0.1100**
- Ensemble Model: **R²: 0.9010**
