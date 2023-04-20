# fintech_project_2


# Overview
> This group project focuses on various aspects machine learning in the financial market. Each group member will examine a different ML aspect and/or paramter for a given issue(s).
***
# Eli - sentiment based analysis
* add here 
* add here

# Mike - Machine learning with a fcous on regression for price prediction.
* A case study using TSCO as underlying issue for analysis
* Examine "manual" ML technique for a given signal/strategy compare to basline performance
* Utilize OpenBB regression predictive model for multiple predictive models.
* Evaluate multiple regression models for price prediction using mean absolute percent error (MAPE) & SHAP plots

# Omar - Training models to predict TSLA stock price
#### Using TSLA technical analysis and price data to train Sequential models with different layers, scalers, and activation functions to find the best for price prediction.
Model_1 - two layers, StandardScaler, and exponential & sigmoid activation functions

* Loss: 15596.7138671875, Accuracy: 0.0

Model_2 - three layers, MinMaxScaler, and elu & tanh & relu activation functions

* Loss: -3014.749755859375, Accuracy: 0.0

Model_3 - ten layers, QuantileTransformer, and only using relu activation functions

* Loss: 100.17599487304688, Accuracy: 0.0

Findings:
* Adding more layers, including the Dropout layers to help with overfitting, and using the same activation function seemed to reduce the loss.
* The QuantileTransformer scaler could have contributed to better model performance for price prediction.
* It is difficult to predict stock prices with accuracy based on technical analysis and price in isolation.

Room for improvements:
* Reducing the data to reduce outliers.
* Experimenting with batch size and shuffle parameters when fitting the model.
* Changing random state, test size, and shuffle when splitting the data.
* Adding or reducing the technical analysis metrics or using different data all together to train the models.
* Testing another model or creating a custom model.
* Utilizing different scaler functions to transform the testing and training datasets.

# Ron - theta model(?)
* add here 
* add here