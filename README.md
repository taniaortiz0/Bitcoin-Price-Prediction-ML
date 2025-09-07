# Bitcoin Price Prediction with Machine Learning and Visualization


# 📃 Table of Contents

1. [Project Overview](#-project-overview)
2. [Files](#-files)
3. [Tools & Libraries](#-tools-&-libraries)
4. [Keynotes](#-keynotes)
5. [Future Improvements](#-future-improvements)

---

# 📘 Project Overview

This project focuses on predicting Bitcoin closing prices using machine learning techniques. By engineering key features such as moving averages, volatility, and lag variables, the project evaluates the predictive power of both Linear Regression and Random Forest models.

The main objectives are:
- Explore how financial indicators influence Bitcoin’s price movements.
- Compare linear and non-linear models for accuracy and reliability.
- Visualize model performance through residuals, feature importance, and correlations.

---

# 📂 Files

- `bitcoin_data.csv` – Historical Bitcoin price and volume dataset.
- `Bitcoin Price Prediction.ipynb` – Jupyter Notebook containing the workflow for data preprocessing, feature engineering, model training, evaluation, and visualization.

---

# ⚙️ Tools & Libraries

- Python (data science workflow)
- Pandas / NumPy – Data preprocessing and feature engineering.
- Scikit-learn – Linear Regression, Random Forest, scaling, and evaluation metrics.
- Matplotlib / Seaborn – Data visualization (predictions, residuals, feature importance, heatmaps).

---

# 📝 Keynotes

- Created target variable (next-day closing price) for supervised learning.

- Engineered financial indicators:
  - MA7 and MA14 (moving averages)
  - Volatility (7-day standard deviation)
  - Lag features (previous day’s closing price)

- Trained and tested models on historical Bitcoin data:
  - Linear Regression achieved strong performance with low error and high R².
  - Random Forest performed poorly, showing signs of overfitting and instability.

- Visualized results with:
  - Predicted vs. actual Bitcoin prices.
  - Residual error distributions.
  - Feature importance scores (Random Forest).
  - Correlation heatmap of features vs. target.

---

# 🚀 Future Improvements

- Explore LSTM/GRU neural networks for sequential modeling of time series.
- Add external indicators (trading volume anomalies, sentiment analysis from social media, global economic factors).
- Improve feature engineering with technical indicators (RSI, MACD, Bollinger Bands).
- Perform hyperparameter tuning (Random Forest, or even Gradient Boosting methods like XGBoost, LightGBM, CatBoost).
- Develop a real-time prediction pipeline for automated crypto price forecasting.
