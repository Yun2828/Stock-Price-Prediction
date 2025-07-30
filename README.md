# Stock-Price-Prediction
Stock Price Prediction model using TensorFlow and Long Short-Term Memory (LSTM) networks

Summary:
- Used keras, tensorflow, numpy, pandas, matplotlib
- Fed the time series data into Recurrent Neural Network (RNN)
- Used TensorFlow to create LSTM models to avoid vanishing gradient issue
- Sliding window technique, grabbing a sequence of 60 previous time steps, to train the model and predict the next step
- Adaptive Moment Estimation, 'adam', to optimize the loss function by minimizing the loss measured by mean_squared_error
- Model Accuracy: RMSE of less than 5


Exploratory Data Analysis on 9 major tech companies: 
<img width="930" height="485" alt="image" src="https://github.com/user-attachments/assets/498e84ed-9e0b-4a58-a979-17aa0d6acd3e" />

<img width="930" height="485" alt="image" src="https://github.com/user-attachments/assets/4e8ed422-0bb7-44ff-99c8-071dfcea1f43" />

The actual and prediction for Cisco stock prices:
<img width="888" height="451" alt="image" src="https://github.com/user-attachments/assets/c0e1a101-25fd-4107-a88b-ab57fcf2858f" />

