# Stock-Price-Prediction
Stock Price Prediction model using TensorFlow and Long Short-Term Memory (LSTM) networks

- Used keras, tensorflow, numpy, pandas, matplotlib
- Fed the time series data into Recurrent Neural Network (RNN)
- Used TensorFlow to create LSTM models to avoid vanishing gradient issue
- Sliding window technique, grabbing a sequence of 60 previous time steps, to train the model and predict the next step
- Adaptive Moment Estimation, 'adam', to optimize the loss function by minimizing the loss measured by mean_squared_error
- Model Accuracy: RMSE of less than 5
