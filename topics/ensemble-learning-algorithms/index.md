# Ensemble learning algorithms

Ensemble learning is a machine learning technique that combines multiple individual models (learners) to make more accurate predictions than each model could on its own. Ensemble learning improves predictive accuracy, robustness, and generalization.

Ensemble learning can be applied to various types of machine learning algorithms, such as decision trees, neural networks, support vector machines, and more.

Some common ones:

* Bagging (Bootstrap Aggregating): Build multiple models in parallel by training each model on a random subset of the training data. Output an average, or do voting to choose a category. Example: Random Forest is an example of a popular bagging-based ensemble method.

* Boosting: Train multiple weak learners sequentially. Each model focuses on the mistakes made by its predecessors. Output a weighted combination of the individual model predictions. Examples: Gradient Boosting Machines (GBM), Extreme Gradient Boosting (XGBoost), LightGBM.

* Stacking (Stacked Generalization): Train base models on the original training data, and their predictions become the new features used to train a meta-model.

* Voting Classifiers (Voting Ensembles): Combine the predictions of multiple models by voting. Use either "hard voting" meaning each model gets one vote, or "soft voting" meaning choose the highest average probability across all models.
