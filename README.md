# Brent-Petrol-LSTM
using LSTM method we forecasted 10 days ahead of brent petrol prices with 2.34 RMSE, 120 epochs, 10 nodes in hidden layers
We scaled the arrayed data, reshaped to 3d and after fitting the model, inverted to 2D and then inverted scaling (fifo transforamtion I would call it). We made predictions using 10 days window timesteps. 
We saved the model in h5 format using h5py library
