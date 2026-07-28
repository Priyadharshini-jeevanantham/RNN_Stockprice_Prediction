# 📈 HCLTech Stock Price Prediction using Recurrent Neural Networks (RNN)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange)
![Keras](https://img.shields.io/badge/Keras-RNN-red)
![NSE](https://img.shields.io/badge/NSE-HCLTECH-green)
![Time Series](https://img.shields.io/badge/Time%20Series-Forecasting-success)

## 📌 Project Overview

This project develops a **Recurrent Neural Network (RNN)** model to predict the stock prices of **HCL Technologies Ltd. (HCLTECH)** listed on the **National Stock Exchange (NSE)**.

Using historical stock market data, the model learns sequential price patterns to forecast future stock prices. The project demonstrates how Deep Learning techniques can be applied to financial time-series forecasting for investment analysis and market trend prediction.

---

# 🎯 Objectives

- Predict future HCLTech stock prices using Deep Learning.
- Learn temporal patterns from historical stock data.
- Evaluate model performance using RMSE.
- Forecast stock prices for the next two months.
- Visualize actual vs. predicted stock prices.

---

# 📊 Dataset

**Source:** National Stock Exchange (NSE)

**Stock:** HCL Technologies Ltd. (HCLTECH)

The dataset contains historical daily trading information, including:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Adjusted Close Price
- Trading Volume

---

# 🧠 Deep Learning Model

The forecasting model is built using a **Simple Recurrent Neural Network (RNN)**.

The workflow includes:

- Data Collection
- Data Cleaning
- Feature Scaling (MinMaxScaler)
- Sequence Generation
- RNN Model Training
- Prediction
- Performance Evaluation
- Future Forecasting

---

# 🏗️ Model Architecture

```
Historical Stock Prices
           │
           ▼
 Data Preprocessing
           │
           ▼
 MinMax Scaling
           │
           ▼
 Sequence Generation
           │
           ▼
 Recurrent Neural Network
           │
           ▼
 Dense Output Layer
           │
           ▼
 Predicted Stock Price
```

---

# 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

# ⚙️ Project Workflow

### Step 1 – Load Historical Data

Historical HCLTech stock prices are loaded for analysis.

---

### Step 2 – Data Preprocessing

- Handle missing values
- Select closing prices
- Normalize data using MinMaxScaler

---

### Step 3 – Sequence Generation

Historical price sequences are created to train the RNN model.

---

### Step 4 – Model Training

The Recurrent Neural Network learns sequential dependencies from historical stock prices.

---

### Step 5 – Prediction

The trained model predicts stock prices on unseen test data.

---

### Step 6 – Future Forecasting

The model forecasts HCLTech stock prices for the **next two months** based on learned trends.

---

# 📈 Model Evaluation

The model performance is evaluated using:

- Root Mean Squared Error (RMSE)
- Training Loss
- Testing Loss
- Prediction Accuracy (Visual Comparison)

---

# 📊 Results

The model successfully learned historical stock price trends and generated future price forecasts.

Key outcomes:

- Accurate learning of sequential stock price movements.
- Effective prediction of future stock prices.
- Low prediction error measured using RMSE.
- Visual comparison of actual and predicted prices demonstrated the model's forecasting capability.

---

# 📊 Performance Metrics

| Metric | Description |
|----------|-------------|
| Training RMSE | Model error on training dataset |
| Testing RMSE | Model error on testing dataset |
| Forecast Horizon | Next 2 Months |
| Model | Simple Recurrent Neural Network (RNN) |

---

# 💡 Key Features

- Time Series Forecasting
- Deep Learning-based Stock Prediction
- Sequential Data Modeling
- RMSE Performance Evaluation
- Future Price Forecasting
- Data Visualization

---

# 🚀 Future Enhancements

- Implement LSTM and GRU models for improved forecasting.
- Incorporate technical indicators such as Moving Averages, RSI, and MACD.
- Use real-time stock market data APIs.
- Build an interactive Streamlit dashboard.
- Compare RNN performance with ARIMA, Prophet, and Transformer-based models.
- Extend forecasting to multiple NSE stocks.

---

# 💼 Skills Demonstrated

- Deep Learning
- Recurrent Neural Networks (RNN)
- Time Series Forecasting
- Financial Data Analysis
- TensorFlow
- Keras
- Python
- Data Preprocessing
- Feature Scaling
- Machine Learning
- Data Visualization
- Predictive Analytics

---

# 📚 References

- National Stock Exchange (NSE)
- TensorFlow Documentation
- Keras Documentation
- Scikit-learn Documentation

---

# 👩‍💻 Author

**Priyadharshini J**
---

# 📜 License

This project is developed for educational and learning purposes.
