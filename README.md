# CU_HW_-DeepLearning_LSTM_stock_predictor
HW for Columbia Engineering - Deep Learning Module - build and train custom LSTM RNNs

Created a stock predictor using a window of closing prices in one model and FNG indicators in another. I first evaluated the models using a window of 10d, epoch of 10 and batch of 1. I then proceeded to experiment with the model architecture and used different hyperparameters to see which would provide the best results. Note that in comparing both models, I used the same set of hyperparameters and model architecture. Per observation, the model that provided the best result was the one using window size 3, epoch of 20 and batch size 5

Evaluation of model performance:

Which model has a lower loss?
The model using closing prices had lower loss with MSE of 0.0053 vs 0.0867 for FNG Index.

Which model tracks the actual values better over time? 
The model using closing prices.

Which window size works best for the model? Window size 3
