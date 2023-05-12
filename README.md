# Deep Learning Time Series Forecasting

This GitHub repository contains the code and data used for a project aimed at building time series regression models to predict future horizons. The project involved conducting exploratory data analysis, feature engineering, and preprocessing. Both linear and non-linear time series forecasting models were explored, including Prophet and Neural Prophet.

## Abstract
This project aimed to build a time series regression model to predict future horizons using a provided dataset. The process involved conducting exploratory data analysis, feature engineering, and preprocessing. Both linear and non-linear time series forecasting models were explored, including Prophet and Neural Prophet. Two variants of each model were developed, including a pre-tuned model and a hyperparameter-tuned model. The models used feature engineered regressor variables such as time-based variables and the provided exogenous variables. Results showed that the Hyperparameter-tuned Neural Prophet model achieved the best performance. 

## Method
The methodology used in this project is depicted in the image below. It outlines the steps involved in data pre-processing, feature engineering, model selection, and model evaluation. 

![Deep Learning Forecasting Methodology](https://github.com/Qunlexie/Deep-Learning-Time-Series-Forecasting/blob/main/Deep%20Learning%20Forecasting%20Methodology.png?raw=true ) 

## Summary
This time series forecasting work evaluated two classes of models: the linear model (Prophet) and the non-linear model (Neural Prophet based on a deep learning architecture). Both tuned and pre-tuned variants of each model were examined, resulting in four models for forecasting the target variable over the next three horizons. The results indicated that the Tuned Neural Prophet model produced the lowest Mean Absolute Error, suggesting that it better captured the non-linear trends in the data.

## Limitations and Future Work
Despite the promising results obtained from this work, there are still opportunities for future work. One direction for future work would be to explore the use of other time series regression models like LSTM, GRU, and ConvLSTM. Additionally, incorporating more exogenous variables or alternative feature engineering techniques, such as time-series cross-validation, may improve the model's performance. Finally, testing the models on larger and more diverse datasets with varying time-series characteristics could also provide more insights into the robustness and generalizability of the models developed in this work.

## Keywords
Time Series Forecasting, Linear Model, Non-Linear Model, Prophet, Neural Prophet, Deep Learning

## Files
- `README.md`: provides an overview of the project, its method, and results.
- `Deep Learning Forecasting Methodology.png`: a diagram outlining the steps taken in the project.
- `data.csv`: the dataset used for this project.
- `time_series_forecasting.ipynb`: a Jupyter notebook containing the code used for data pre-processing, feature engineering, model selection, and model evaluation.
