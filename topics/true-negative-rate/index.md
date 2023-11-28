# True negative rate (TNR)

The term "true negative rate" (TNR) is a metric used in the evaluation of machine learning models, particularly in the context of binary classification problems. It is also known as specificity or the correct rejection rate. The true-negative rate measures the proportion of actual negative instances that are correctly identified as negative by the model out of the total actual negative instances.

The formula for calculating the true-negative rate is:

$$TNR=\frac{TrueNegatives}(TrueNegatives+FalsePositives}$$

Where:

* True Negatives (TN): The number of instances that are actually negative and are correctly identified as negative by the model.

* False Positives (FP): The number of instances that are actually negative but are incorrectly identified as positive by the model.

The true-negative rate provides insights into how well a model performs in correctly identifying negative instances. In some applications, the cost or consequences of false positives (misclassifying actual negatives as positives) may be high, and TNR becomes an important metric for assessing model performance.

It's common to consider both sensitivity (true positive rate) and specificity (true negative rate) together to get a more comprehensive view of a model's performance. The balance between sensitivity and specificity is often crucial, and the choice of evaluation metrics depends on the specific goals and requirements of the task at hand.
