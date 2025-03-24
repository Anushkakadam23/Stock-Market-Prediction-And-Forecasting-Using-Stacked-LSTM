# 📈 Stock Market Prediction using Stacked LSTM

## 📌 Overview
This project implements a **Stock Market Price Prediction Model** using a **Stacked LSTM (Long Short-Term Memory) network**.  
The model is trained on **Apple (AAPL) stock prices** to predict future trends.

## 📊 Dataset
- The dataset is fetched using **Tiingo API**.
- Contains **closing prices** from `2015-01-01` to `2025-03-21`.
- Data is **scaled** using MinMaxScaler for better LSTM training.

## ⚙️ Project Workflow
1️⃣ **Fetch stock price data** from Tiingo API  
2️⃣ **Preprocess data** (Normalization, Splitting)  
3️⃣ **Create time-series sequences**  
4️⃣ **Train a Stacked LSTM Model**  
5️⃣ **Evaluate using RMSE (Root Mean Squared Error)**  
6️⃣ **Plot actual vs predicted values**  
7️⃣ **Predict future stock prices (Next 30 days)**  

## 🏗️ Model Architecture
- **LSTM Layer 1** → 50 Units, Return Sequences ✅  
- **LSTM Layer 2** → 50 Units, Return Sequences ✅  
- **LSTM Layer 3** → 50 Units, Final Layer ✅  
- **Dense Layer** → Fully Connected Output Layer ✅  
- **Optimizer** → Adam  
- **Loss Function** → Mean Squared Error (MSE)  

