Abstract

Predicting the likelihood of crimes occurring in a given area at a specific time can be a
valuable tool for law enforcement agencies, allowing them to allocate resources more
efficiently and potentially prevent crimes from occurring. In this project, we use
machine learning and time-series forecasting techniques to build a model that can
predict the likelihood of crimes occurring at a specific location and time in the future.
We gather data on the location, type, and time of crimes that have occurred in the past,
as well as other relevant information such as weather data, population density, and
socioeconomic indicators. Our model is trained on this data and can make predictions
about future crime occurrences. We evaluate the effectiveness of our model in its ability
to predict crimes accurately and its usefulness in informing law enforcement decisions.
Our results show that our model can accurately predict crime occurrences and can
potentially be a valuable resource for law enforcement agencies.


Introduction

Problem Statement
Crime is a pervasive issue that affects communities worldwide, and despite efforts to
combat it, it continues to persist. The use of machine learning and time-series
forecasting techniques has the potential to provide valuable insights and aid in
decision-making for law enforcement agencies to address this problem. However, there
is still a lack of research evaluating the effectiveness of these techniques in predicting
criminal activity.

Background
Various studies have been conducted on crime prediction, including using pattern-based
density models, spatiotemporal event analysis, and classification techniques like Naive
Bayes and Neural Networks. Time series analysis has also been used, with the ARIMA
model being a popular choice. Data mining techniques have also shown promise in
identifying crime "hot spots" and yielding significant findings from crime report
databases.
While some studies have examined the causes and consequences of crime, there is still a
need for research to evaluate the effectiveness of machine learning and time-series
forecasting techniques for crime prediction. This final project report aims to address this
gap by evaluating the efficacy of these techniques in predicting criminal activity and
providing insights for law enforcement agencies to make data-driven decisions.


Proposed Work
The proposed work aims to develop a crime forecasting and analysis system using
machine learning algorithms. The system will be trained on historical crime data and
various other datasets such as weather data and geospatial data to predict future criminal
activities. The following research papers will be used as a reference to develop the
proposed system.

Methodology
We have used the Los Angeles Crime Data from 2010 to 2019 which was openly
available on Kaggle. The dataset includes various parameters including the Date of
Crime, Type of crime, and areas in which it occurs. We have used time-series forecasting
to predict the crimes occurring in the future. For this, we have used two models. ARIMA
and the Facebook Prophet model. Both Prophet and ARIMA (Autoregressive Integrated
Moving Average) are time series forecasting methods that can be used to predict the
future values of a series based on its past values.

Prophet is a library developed by Facebook that is specifically designed for forecasting
time series data. It is based on a decomposable time series model that is fit to the data
using a variant of the Generalized Additive Model (GAM) optimization algorithm. The
Prophet model decomposes the time series into trend, seasonality, and holidays
components, and then fits a linear model to predict the trend component. The seasonality
and holidays components are then added back in to produce the final forecast.

ARIMA is a widely used statistical method for time series forecasting. It is a linear
model that is fit to the data using the maximum likelihood estimation method. ARIMA
models are based on the idea that the time series can be decomposed into three
components: trend, seasonality, and noise. An ARIMA model is specified by three
integers (p, d, q), which represent the order of the autoregressive (AR) component, the
degree of difference, and the order of the moving average (MA) component,
respectively. The model is fit to the data by finding the values of these three integers that
minimize the sum of the squared errors between the predicted and actual values.

Random forest is an ensemble learning algorithm that constructs multiple decision trees
and averages their outputs to make a final prediction. In the context of time series
forecasting, random forest regressor can be used to predict future values based on
historical time series data, along with other relevant features such as seasonality, trend,
and external factors. Random forest regressor is often used in cases where the time
series data has a non-linear relationship with the target variable, and where there may be
multiple interacting features that impact the target variable.

Long Short-Term Memory (LSTM) is a type of recurrent neural network (RNN)
architecture that is designed to handle sequential data, such as time series. LSTM is
well-suited for time series forecasting tasks as it is able to capture long-term
dependencies and patterns in the data over time. LSTM has been shown to be effective
in handling complex time series data with multiple input variables and non-linear
relationships. LSTM models typically require more data and training time compared to
other algorithms, but can deliver highly accurate predictions in some cases.

XGBoost is a popular gradient boosting algorithm that is often used in time series
forecasting. Gradient boosting is an ensemble learning technique that combines multiple
weak models into a stronger model. XGBoost is designed to handle both regression and
classification problems, and can be used to predict future values in a time series.
XGBoost is known for its ability to handle high-dimensional data and non-linear
relationships between features and the target variable. It is often used in cases where
there are many input variables, and where the relationship between the input variables
and target variable is complex.
