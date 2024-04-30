# Stock-Market-Prediction-And-Forecasting-Using-Stacked-LSTM
This repository contains a deep learning model implemented in Keras for sequence prediction and time series forecasting tasks. The model utilizes stacked Long Short-Term Memory (LSTM) layers to capture temporal dependencies in the data. It's trained with the Adam optimizer and mean squared error (MSE) loss.

Methods:

In this project, the data preparation phase involved collecting and preprocessing time series or sequential data. This included handling missing values, outliers, and inconsistencies, as well as engineering relevant features from the raw data. For the model architecture, a deep learning approach using Keras was adopted. Long Short-Term Memory (LSTM) layers were utilized to capture temporal dependencies within the data. These layers were stacked using the Sequential API to learn hierarchical representations, with a dense output layer added for final predictions.

During the training procedure, the Adam optimizer was employed for its effectiveness in training deep learning models. Mean Squared Error (MSE) served as the loss function to measure prediction accuracy. Additionally, metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) were monitored throughout training to assess model performance.

Definitions:

Long Short-Term Memory (LSTM) networks are a type of recurrent neural network (RNN) architecture designed to process and predict sequential data. Unlike traditional RNNs, LSTM networks can capture long-term dependencies in the data by utilizing a memory cell and various gating mechanisms.

An optimizer is an algorithm used to adjust the parameters of a neural network during training to minimize the error between the model's predictions and the actual target values. The Adam optimizer, chosen for this project, is known for its effectiveness in training deep learning models.

The loss function quantifies the model's performance during training by measuring the difference between its predictions and the actual target values. Mean Squared Error (MSE) was selected as the loss function in this project, calculating the average squared difference between predicted and actual values.
