+++
title = 'Time Series Temperature Forecasting (LSTM)'
date = 2024-06-15
PublishDate = 2024-08-15
draft = true
+++
Developed a deep learning model for univariate time series forecasting using a stacked LSTM architecture to predict daily temperature trends. The project incorporated three LSTM layers and dense layers for improved temporal feature extraction and regression accuracy. Careful attention was given to input-output dimensionality using the return_sequences parameter and 1D output neuron configuration. EarlyStopping was implemented to optimize training time and avoid overfitting. Data normalization techniques, such as RobustScaler and outlier handling, were applied to ensure stable and reliable forecasting, especially for non-normally distributed data. Performance was validated on real-world temperature data using RMSE metrics, and the model was evaluated across training, validation, and test splits. This project highlights the effectiveness of LSTM networks in weather-related predictive modeling and contributes toward advancing applications in environmental time series forecasting.





