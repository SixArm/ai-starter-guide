# Mean Squared Error (MSE)

Mean Squared Error (MSE) is a commonly used performance metric for regression problems in machine learning. It measures the average squared difference between the predicted values and the actual (ground truth) values.

MSE is particularly useful for evaluating how well a regression model's predictions match the true values and how much error is present in the predictions. Lower MSE indicates predictions are closer to the true values. Higher MSE indicates predictions are farther from the true values.

Formula:

* $\operatorname{MSE}=\frac{1}{n} \sum_{i=1}^n \left(Y_i-\hat{Y_i}\right)^2$

* $n$ is the number of data points (samples) in the dataset.

* $Y_i$ is the actual value of the target variable for the i-th data point.

* $\hat{Y_i}$ is the predicted value of the target variable for the i-th data point.

The steps to calculate MSE are as follows:

* Make predictions using the regression model.

* For each data point, compute the difference between the actual value and predicted value, then square it.

* Sum the squared differences, then divide by the number of data points.
