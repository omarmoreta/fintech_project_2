# fintech_project_2


# Overview
> This group project focuses on various aspects machine learning in the financial market. Each group member will examine a different ML aspect and/or paramter for a given issue(s).
***
# Eli - sentiment based analysis
Summary:
* Backstory into why I focus on sentiment so much
* Walkthrough of how sentiment in the news can impact investment decision making
* We'll talk about how you can use this information to train models for future use

Results:
* There are some significant flags from the fluctuations in price over 3 days
* We're able to see how the TextBlob mechanism may not accurately label new articles

Improvements:
* There's plenty of opportunity to help train the model on results classified manually as positive/negative sentiment
* Ensuring that articles align with the correct stock
* Expanding on the impact from the sentiment/news on investments

# Mike - Machine learning with a fcous on regression for price prediction.
Summary:
* A case study using TSCO as underlying issue for analysis
* Examine "manual" ML technique for a given signal/strategy compare to basline performance
* Utilize OpenBB regression machine learning model to predict future price with multiple models.
* Evaluate multiple regression models for price prediction using mean absolute percent error (MAPE) & SHAP plots

Results:
* Using the SHAP plot for regression models we can quickly determine the features with greatest impact on a given model.
* Utilizing the MAPE value as metric for measurement of model quality, we can evaluate multiple model parms (train split, covariates, length of prediction...) efficiently & quantitatively for effect.
* SHAP & MAPE findings can be used to guide future model construction.

Improvements:
* The next step in the analysis would be to examine/add multiple new features to the model and examine impact on model accuracy.
* As this was just a regression model analysis, another step would be to examine other predictive models and or neural networks.
* Once a model is found that achieves an acceptable accuracy/MAPE, trading strategies could be developed around model predictions.

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