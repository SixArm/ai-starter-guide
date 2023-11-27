# Lazy learning algorithms

Lazy learning algorithms are a subset of machine learning algorithms that make predictions based on the similarity between new data instances and the training data. Lazy learning algorithms store the entire training dataset and use it directly to make predictions when new data is encountered. These algorithms contrast with eager learning algorithms, which build a model during the training phase, then use the model to make predictions.

Common examples of lazy learning algorithms include: k-Nearest Neighbors (k-NN), Case-Based Reasoning, and locally weighted regression. Lazy learning algorithms are also known as instance-based learning algorithms or memory-based learning algorithms.

Key characteristics:

* No Explicit Model: Lazy learning algorithms do not create an explicit model during training. They simply store the training instances and their associated labels.

* Non-parametric: Lazy learning algorithms do not assume any specific functional form for the underlying data distribution, making them more flexible in capturing complex relationships.

* Adaptability: Lazy learning algorithms can adapt to changes in the training data without requiring a retraining phase. They automatically incorporate new data as it becomes available.

* Memory Intensive: Since lazy learners store the entire training dataset, they can be memory-intensive and may have slower prediction times compared to eager learners.

* Local Information: Lazy learning algorithms often focus on local information within the training data, which can make them effective for tasks where the decision boundary is complex and data distribution is non-uniform.
