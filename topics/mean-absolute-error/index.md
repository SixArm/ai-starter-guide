# Mean Absolute Error (MAE)

Mean Absolute Error (MAE) is a common performance metric used in regression tasks to evaluate the accuracy of a model's predictions. It measures the average absolute difference between the predicted values and the actual (ground truth) values. MAE is also known as the L1 loss or L1 norm.

MAE is particularly useful for evaluating how well a regression model's predictions match the true values and how much error is present in the predictions. Lower MAE indicates predictions are closer to the true values. Higher MAE indicates predictions are farther from the true values.

MAE is a robust metric because it does not penalize outliers as much as Mean Squared Error (MSE), which squares the differences between predicted and actual values. As a result, MAE is less sensitive to extreme values in the data.

Formula:

* $\operatorname{MAE}=\frac{1}{n} \sum_{i=1}^n |Y_i-\hat{Y_i}|$

* $n$ is the number of data points (samples) in the dataset.

* $Y_i$ is the actual value of the target variable for the i-th data point.

* $\hat{Y_i}$ is the predicted value of the target variable for the i-th data point.

The steps to calculate MAE are as follows:

* Make predictions using the regression model.

* For each data point, compute the difference between the actual value and predicted value.

* Sum the differences, then divide by the number of data points.

