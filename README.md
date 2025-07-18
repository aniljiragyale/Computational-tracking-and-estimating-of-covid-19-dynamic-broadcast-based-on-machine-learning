# Computational Tracking and Estimating of COVID-19 Dynamic Broadcast Based on Machine Learning

This project focuses on computational tracking and estimation of the COVID-19 spread using machine learning and deep learning models. It applies time-series forecasting techniques to predict future case trends, helping visualize and understand the dynamics of the pandemic.

## 🎯 Objective

To design a system that:
- Tracks COVID-19 case data over time
- Predicts future cases using various models
- Visualizes trends for actionable insights

## 🔍 Models Used

- **LSTM (Long Short-Term Memory)**: For time-series based forecasting using deep learning
- **Lasso Regression**: To perform linear regression with L1 regularization
- **ARIMA (AutoRegressive Integrated Moving Average)**: For classical time-series forecasting

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data processing
- **Matplotlib**, **Seaborn** – Visualization
- **scikit-learn** – Lasso Regression
- **statsmodels** – ARIMA modeling
- **TensorFlow / Keras** – LSTM modeling
- **Jupyter Notebook** – Experimentation

## 📁 Project Structure

📁 covid19-forecasting/
├── data/ # Raw and processed datasets
├── models/ # Saved model files
├── notebooks/ # Jupyter notebooks for each model
├── app/ # Flask app (if deployed as a web app)
├── templates/ # HTML templates (Flask)
├── static/ # CSS/JS/images
├── requirements.txt # Dependencies
└── README.md # Project documentation

om ARIMA and LSTM

Actual vs predicted graphs

Error metrics comparison (MAE, RMSE)

Visualization of model performance

📈 Evaluation Metrics
Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score (for Lasso)
