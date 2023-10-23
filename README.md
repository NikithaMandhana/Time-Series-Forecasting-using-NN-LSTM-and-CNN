# Time-Series-Forecasting-using-NN-LSTM-and-CNN
 
This project is threefold: 
• Task 1: Predict [Close] of a day based on the last 7 days’ data [Open, High, Low, Volume, Close] using a full-connected neural network model. In other words, we want to predict the price in the green cell using all the numbers in the red cell. Use the first 70% of the available records for training and the remaining 30% of the available records for test. Each record has 7 * 5 = 35 input features and 1 output feature. 

• Task 2: Same as Task 1 but uses a LSTM model. Each record can be viewed as a sequence of 7 vectors, each vector with 5 dimensions.

• Task 3: Same as Task 1 but uses a CNN model.

For all the three models we have reported the RMSE of the model and shown the regression lift chart of the test data. The red cell can be viewed as a 1D image of 7 pixels, each pixel with 5 channels, or as 
a 2D image of 7 * 5 = 35 pixels, each pixel with 1 channel. 
