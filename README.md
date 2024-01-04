# Multi-Step-Air-Quality-Forecasting-Using-Robust-LSTM-Model
Given a dataset that records information related to air quality over time for four cities: B, G, S, and T. The challenge is to develop a robust deep-learning model for multi-step forecasting in multivariate time series data.

To test the Model on the datasets: <br>
i)   Load the dataset <br>
ii)  Preprocess the dataset: <br>
		Encode the categorical values <br>
		Convert to Pandas dataframe <br>
		Label the columns/attributes to x1,x2,... <br>
		Convert the attribute to the shape of (Rows * 1) <br>
		Scale the numerical values to 0-1 <br>
		Finally, Horizontally stack columns <br>
iii) Now, Pass the testing data to split_sequences() function. <br>
     The Function parameters are already defined in the notebook. <br>
iv)  Predict the data and transform back to original form and then compare for the results <br>

# See the notebook for more reference...
