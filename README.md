# Time-series-Based-Drought-Forecasting
> ## This work is A time series-based forecasting model to predict a future drought condition and make analysis by forecasting the indices that indicate the drought conditions in Borena Zone, Ethiopia.
There are several specificities in time-series modeling based on the nature of time-series data.
##### Univariate
> The **univariate time series** consists of a single observation over some time. The term univariate refers to the analysis of one variable. Univariate time series are a dataset comprised of a single series of observations with a temporal ordering and a model is required to learn from the series of past observations to predict the next value in the sequence.
> Univariate time series models are forecasting models that use only one target variable and its temporal variation to forecast the future. Univariate models are specific to time series.
##### Multivariate  
> The **multivariate time series** consists of more than one observation collected over time. The term multivariate refers to the analysis of more than one variable. Multivariate Time Series models are the Univariate Time Series models that are adapted to integrate external variables. Supervised machine learning can be also used for this task.
> Multivariate time series data means data where there is more than one observation for each time step.
##### SK-forecast
> **SK-forecast** is a Python library that gives the power for Scikit-learn repressors to act as single and multi-step forecasters. Many regression algorithms can be used for forecasting, but when it comes to time series analysis it can still be so challenging. The SKforecast python library provides a comprehensive set of tools for training, validation, and prediction in a variety of scenarios commonly encountered when working with time series.
> The library is built using the widely used scikit-learn API which makes it easy to integrate into existing workflows. Users can access a range of functionalities such as feature engineering, model selection, hyperparameter tuning, and others, using the skforecast library. Additionally, skforecast is developed according to the following priorities:
1. Fast and robust prototyping
2. Validation and back-testing methods to have a realistic assessment of model performance
3. Sk-forecast also works with any regression algorithms compatible with the scikit-learn API such as RandomForest, LightGBM, XGBoost, CatBoost, etc.
##### Here are the tools, the programming language, installed packages, and dependencies. 
* Software tool: Google Collaboratory
* Programming language: python == 3.10.12
**Installed packages and dependencies**
- keras==2.15.0
- lightgbm==4.1.0
- pandas == 1.5.3
- numpy==1.25.2
- sci-kit-learn==1.2.2
- sklearn-pandas==2.2.0
- TensorFlow == 2.15.0
tf-keras==2.15.0, skforecast=0.11.0, xgboost==2.0.3, matplotlib==3.7.1, keras-tuner=1.4.6, catboost==1.2.3
