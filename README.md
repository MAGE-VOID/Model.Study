# Model.Study

Library Import:

Imports various libraries for data analysis (pandas, numpy, seaborn, etc.) and specific tools for financial analysis and time series modeling (statsmodels, MetaTrader5, keras).
Data Collection:

Uses the MetaTrader5 library to obtain exchange rate data for the given symbols (in this case "EURUSD" and "EURJPY") in the specified date range.
Data Preprocessing:

Concatenates the data for all symbols into a single DataFrame.
Perform some transformations on the numerical columns, standardizing the data for each symbol.
Plot standardized data.
Analysis of data:

Performs descriptive statistical analysis, including measures of central tendency and dispersion.
Plot histograms to visualize the distribution of data.
Use the seaborn library to visualize the relationship between different variables.
Decomposition of Time Series:

It uses additive seasonal decomposition to decompose the close time series into components such as trend, seasonality and residuals.
Visualization of Decomposed Data:

Plot the decomposed components of the time series.
Time Series Modeling with Neural Networks:

It uses LSTM (Long Short-Term Memory), LSTM with attention, and RNN (Simple Recurrent Neural Network) neural network models to predict future values ​​of the time series.
Train the models and evaluate their performance using training and test sets.
Viewing Model Results:

Plots the model predictions against the actual values ​​on a test set.
Additional Display:

It performs several additional visualizations, including line graphs for different columns of data and a pair plot to explore relationships between variables.