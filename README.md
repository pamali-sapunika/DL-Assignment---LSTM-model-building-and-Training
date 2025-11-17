### Deep Learing Assignment - LSTM Training

Implementation of an LSTM-based neural network for sequence modeling. Designed for training and evaluating time-series and sequence based dataset: Austrelian Rainfall Dataset (weatherAUS.csv)

Austrelian Rainfall Dataset: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package 
</br>🌧️This dataset includes about 10 years of daily weather observations from numerous Australian weather stations.

</br>🎯 Target variable - RainTomorrow (Rain next day, Yes or No?)
Number of input features: 23 (MaxTemp, MinTemp, Evaporation, Sunshine, WindGustDir, WindGustSpeed, WindDir9am...)
Number of data samples(rows): 145461

</br>✨ Features include, 
data preprocessing pipelines(Handling missing values, Remove duplicates, Preprocess categorical columns, Preprocess numerical columns) 
<ul><li>Class imbalance handling,
<li>hyperparameter tuning, 
<li>training loops, 
<li>early stopping, 
<li>performance metrics, 
<li>and visualizations for loss/accuracy trends
