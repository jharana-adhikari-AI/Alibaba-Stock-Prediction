````markdown
# Alibaba Stock Price Prediction

## Overview
This project predicts Alibaba Group's stock prices using historical data (2014-2025) with time series models, including ARIMA, SARIMA, LSTM, and RNN. The dataset is sourced from Yahoo Finance, and the models are evaluated using MAE and RMSE.

## Dataset
The dataset used for this project is sourced from Kaggle:
[Alibaba Stock Dataset - Kaggle](https://www.kaggle.com/datasets/mhassansaboor/alibaba-stock-dataset-2025?select=Ali_Baba_Stock_Data.csv)

## Steps Followed
1. **Data Collection:** Loaded historical stock price data using pandas.
2. **Data Cleaning:** Handled missing values, removed duplicates, and ensured data integrity.
3. **Exploratory Data Analysis (EDA):** Visualized stock trends over time.
4. **Model Building:** Implemented ARIMA, SARIMA, LSTM, and RNN models.
5. **Model Evaluation:** Compared models using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Model Performance

| Model   | MAE   | RMSE  |
|---------|-------|-------|
| ARIMA   | 29.35 | 31.25 |
| SARIMA  | 21.88 | 23.83 |
| LSTM    | 2.33  | 3.30  |
| RNN     | 2.05  | 2.61  |

The results indicate that deep learning models (LSTM and RNN) significantly outperform traditional time series models (ARIMA and SARIMA).

## Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Statsmodels (ARIMA, SARIMA)
- TensorFlow & Keras (LSTM, RNN)

## How to Use
1. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels tensorflow
   ```
2. Run the Jupyter Notebook to preprocess data, train models, and evaluate performance.
3. Modify hyperparameters to improve model accuracy.

## Future Work
- Incorporate external factors (news sentiment, macroeconomic indicators).
- Implement more advanced deep learning models like Transformers.
- Optimize hyperparameters for better performance.

## Contributors
- Jharana Adhikari https://www.linkedin.com/in/jharana-adhikari 

## License
This project is open-source and available under the MIT License.
````

