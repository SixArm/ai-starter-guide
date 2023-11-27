# Loss Function

A loss function, also known as a cost function or objective function, is a component in the training process of a machine learning model. It quantifies the discrepancy between the predicted output of the model and the actual (ground truth) target values for a given set of input samples.

The loss function serves as a guide for the model optimization algorithm (such as gradient descent) to adjust the model's parameters iteratively. The process continues until the model reaches a point where further updates do not significantly reduce the loss.

Typical loss functions…

Regression Tasks:

* Mean Squared Error (MSE): Measures the average squared difference between predicted and actual values.
* Mean Absolute Error (MAE): Measures the average absolute difference between predicted and actual values.
* Huber Loss: Combines the characteristics of MSE and MAE, providing a balance between the two.

Binary Classification Tasks:

* Binary Cross-Entropy Loss (Log Loss): Measures the dissimilarity between the predicted probabilities and the true binary labels.
* Hinge Loss (used in SVM): Encourages correct classification by penalizing misclassifications.

Multiclass Classification Tasks:

* Categorical Cross-Entropy Loss: Measures the dissimilarity between predicted probabilities and one-hot encoded target labels.

Clustering Tasks:

* K-means Loss: Measures the distance between data points and cluster centroids.
