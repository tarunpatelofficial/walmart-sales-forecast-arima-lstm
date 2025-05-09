# Walmart Sales Forecasting using ARIMA and LSTM

This project explores time series forecasting techniques on Walmart retail sales data. It uses both traditional statistical models (ARIMA) and deep learning models (LSTM) to predict future sales across different stores and departments.

## 📁 Dataset

The dataset includes:
- `features.csv`: Additional data related to each store.
- `stores.csv`: Metadata about Walmart stores.
- `train.csv`: Historical sales data used for training.
- `test.csv`: Test data for validation.
- `Walmart_Sales.csv`: Combined dataset for LSTM modeling.

## 🧠 Models Used

### ARIMA (AutoRegressive Integrated Moving Average)
- Implemented in `ARIMA.ipynb`
- Focuses on classical time series forecasting with parameter tuning.

### LSTM (Long Short-Term Memory)
- Implemented in `LSTM.ipynb`
- Uses TensorFlow/Keras to model sequential data and predict future trends.

## 🧰 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib, Seaborn
- Statsmodels (for ARIMA)
- TensorFlow/Keras (for LSTM)
- Scikit-learn

## 🧪 How to Run

1. Clone the repository
```bash
git clone https://github.com/yourusername/walmart-sales-forecast-arima-lstm.git
cd walmart-sales-forecast-arima-lstm
