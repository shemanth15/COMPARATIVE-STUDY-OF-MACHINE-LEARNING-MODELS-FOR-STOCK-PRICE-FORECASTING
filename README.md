# COMPARATIVE-STUDY-OF-MACHINE-LEARNING-MODELS-FOR-STOCK-PRICE-FORECASTING
This project focuses on building a real-time stock price prediction system using Machine Learning and Deep Learning techniques. The objective is to analyze historical stock market data, Historical stock data is collected using the yfinance API, which provides key market attributes such as Open, High, Low, Close prices, and trading Volume
📌 Project Overview

This project focuses on building a real-time stock price prediction system using Machine Learning and Deep Learning techniques. The system analyzes historical stock market data, applies advanced feature engineering, and trains multiple models to generate accurate predictions for trading decision support.

The main objective of this project is to compare different machine learning approaches and evaluate their performance in predicting stock trends.

📊 Data Collection

Historical stock market data is collected using the yfinance API.

The dataset includes the following features:

Open

High

Low

Close

Volume

These features represent daily trading activity and serve as the primary inputs for the prediction models.

⚙️ Feature Engineering

To enhance prediction accuracy, the following technical indicators are generated:

RSI (Relative Strength Index) – Measures momentum

MACD (Moving Average Convergence Divergence) – Identifies trend direction

Bollinger Bands – Captures volatility

Additionally, time-based cyclical encoding (sine & cosine transformation) is applied to represent periodic patterns such as days and months.

🧹 Data Preprocessing

The dataset undergoes the following preprocessing steps:

Handling missing values

Feature scaling using StandardScaler

Dimensionality reduction using Principal Component Analysis (PCA)

Train-test data splitting

These steps improve model performance and computational efficiency.

🤖 Models Used

The following models are implemented and compared:

LSTM (Long Short-Term Memory) – For time-series forecasting

Support Vector Machine (SVM) – For trend classification

Gradient Boosting Classifier – For enhanced ensemble learning performance

📏 Evaluation Metrics

Model performance is evaluated using:

Accuracy

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R-Squared (R²)

🚀 Deployment

The trained model is integrated into a real-time prediction system capable of analyzing live stock data and generating predictive signals for trading platforms.

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

TensorFlow / Keras

XGBoost

yfinance

Matplotlib
