# Bitcoin Price Prediction and Strategy Backtesting with LSTM

This project demonstrates a deep learning approach to forecast Bitcoin prices using an LSTM (Long Short-Term Memory) model, followed by a backtesting strategy to evaluate the effectiveness of the predictions in a simulated trading environment.

---

## 📌 Project Structure

- **Notebook 1: `lstm-approach.ipynb`**  
  Builds and trains an LSTM model for Bitcoin price prediction using historical time-series data.

- **Notebook 2: `back-testing.ipynb`**  
  Implements a trading strategy based on model predictions and evaluates its performance using the `Backtrader` library.

---

## 🧠 Tech Stack

- Python
- Keras & TensorFlow (LSTM Model)
- Pandas, NumPy, Matplotlib
- Backtrader (Backtesting framework)
- Scikit-learn (Data scaling and preprocessing)

---

## 📈 Workflow

1. **Data Preprocessing**  
   - Historical Bitcoin price data cleaned and normalized.
   - Converted to sequences suitable for time-series prediction.

2. **LSTM Model Development**  
   - LSTM network built with multiple layers.
   - Trained on past Bitcoin data to predict future closing prices.
   - Evaluated with MSE and RMSE metrics.

3. **Trading Strategy & Backtesting**  
   - Predicted future prices are used to generate Buy/Sell signals.
   - Strategy tested on historical data using Backtrader.
   - Performance assessed with key financial metrics.

---

## ✅ Results

- **LSTM Model Performance**
  - MAE: *122.76*  
  - MAPE: *0.36%*  
  - The model was able to capture general trends in price movement with decent forecasting ability.

- **Backtesting Results**
  - Strategy Return: **+45.44%**  
  - Sharpe Ratio: **3.12**  
  - The strategy showed profitable results.

---

## 🚀 How to USE

Start with lstm-approach.ipynb to train and evaluate the model.

Proceed to back-testing.ipynb to simulate trades based on predictions.
