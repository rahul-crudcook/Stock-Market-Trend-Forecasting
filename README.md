# Stock Market Trend Forecasting

This project explores the application of various time series forecasting models to predict stock market trends. Utilizing a historical dataset, we aim to analyze stock price movements and develop forecasting models that can provide insights into future trends.

## Models Explored

1. **Moving Averages and Exponential Smoothing**
   - Utilized for smoothing the time series and identifying trends.

2. **Holt's Linear Trend Model**
   - Extends exponential smoothing to capture data trends.

3. **Holt-Winters Method**
   - Incorporates triple exponential smoothing to model both trends and seasonality.

4. **ARIMA (AutoRegressive Integrated Moving Average)**
   - A statistical approach for modeling and forecasting time series data.

5. **LSTM (Long Short-Term Memory) Networks**
   - A recurrent neural network architecture used for sequence prediction problems.

6. **Prophet**
   - A decomposable model for time series forecasting that handles trends, seasonality, and holidays.

## Performance Metrics

The models were evaluated based on their Root Mean Squared Error (RMSE) to quantify the prediction accuracy.

## Results Summary

- The LSTM model achieved an RMSE of approximately 39.32, indicating a relatively accurate prediction capability.
- The Prophet model yielded an RMSE of 124.048, which was less accurate in comparison to the LSTM model for the given dataset.


## Conclusion

The LSTM model showed the best performance among the models tested in this project, providing a promising tool for stock market trend forecasting.

## How to Use

To replicate the findings of this project:
1. Ensure you have the required data in a format compatible with the models.
2. Run the preprocessing script to prepare your data.
3. Execute the model building script to train and save your models.
4. Evaluate the models using the evaluation script.
5. Visualize the results with the visualization script.

## Dependencies

- Python 3.8+
- NumPy
- pandas
- Matplotlib
- scikit-learn
- TensorFlow
- Keras
- Prophet