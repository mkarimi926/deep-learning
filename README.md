# deep-learning
Comparison of GRU, BGRU, BGRU-ATT, LSTM, BLSTM, BLSTM-ATT, BLSTM-TRA, BGRU-ATT models for wind speed prediction

In this project I have created a deep learning time series analysis environment with the following features:
### I have used daily dataset for wind speed in Berlin
### Descriptive analysis of features are included
### Some plots displaying the change of features during dates are prepared
### Feature engineering is done based on day of week, month, previous values of wind speed and rolling mean of wind speed
### To better display the cyclic features of created variables I used their Sine and Cosine
### To get better convergence in the model, the training and test data are scaled using minmax scaler
### The look back period for model is parametric and it can be set by watch_back variable. Now, it is set to 1 days.
### Number of features used for prediction is parametric and it can be adjusted using <features> variable.
### The models have few layers and include different combination of LSTM, GRU, Bi-Directional, Attention and Transformer
### Performance of all models is compared using Validation-Loss diagrams
### The result of the models are compared with test data vs. prediction diagrams
### Number of epochs for all models can be adjusted through global_epochs variable
### All the models are compared based on RMSE, MAE and Correlation-Coefficient
