# RMSE (Root mean squared error) , Mean Absolute Error (MAE) ,  Mean Squared Error (MSE) : 



<h2> (1.) RMSE (Root Mean Squared error): </h2>

 
 ```
 Root mean square error or root mean square deviation is one of the most commonly used measures for evaluating the quality of predictions. It shows how far predictions fall from measured true values using Euclidean distance.

To compute RMSE, calculate the residual (difference between prediction and truth) for each data point, compute the norm of residual for each data point, compute the mean of residuals and take the square root of that mean. RMSE is commonly used in supervised learning applications, as RMSE uses and needs true measurements at each predicted data point.

Root mean square error can be expressed as where N is the number of data points, y(i) is the i-th measurement, and y ̂(i) is its corresponding prediction.

Note: RMSE is NOT scale invariant and hence comparison of models using this measure is affected by the scale of the data. For this reason, RMSE is commonly used over standardized data.
 
 ```
 
 ![image](https://github.com/Darshan0902/RMSE-MAE-MSE-using-Python/assets/77969007/27ff571c-10d0-4bde-8f37-7bfb1a783091)


# <h2> (2.)  Mean Absolute Error (MAE) </h2> : 

```

In the context of machine learning, absolute error refers to the magnitude of difference between the prediction of an observation and the true value of that observation. MAE takes the average of absolute errors for a group of predictions and observations as a measurement of the magnitude of errors for the entire group. MAE can also be referred as L1 loss function.


```

<h2> (3.) Mean Squared Error (MSE) </h2> : 
 
 
 ```
 
 The average squared difference between the estimated values and the actual value. MSE is a risk function, corresponding to the expected value of the squared error loss. The fact that MSE is almost always strictly positive (and not zero) is because of randomness or because the estimator does not account for information that could produce a more accurate estimate.

 
 ```
