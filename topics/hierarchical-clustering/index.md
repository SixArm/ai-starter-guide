# Hierarchical clustering

Hierarchical clustering is a technique in the field of unsupervised machine learning and data analysis. It groups similar data points into clusters based on their similarity or distance. The result of hierarchical clustering is typically represented as a dendrogram, a tree-like diagram that visually shows the arrangement of clusters at different levels of granularity.

Hierarchical clustering is widely used in various fields, including biology, social sciences, marketing, and more, for tasks such as customer segmentation, gene expression analysis, and image segmentation.

There are two main approaches: agglomerative hierarchical clustering which is bottom-up, and divisive hierarchical clustering which is top-down approach.

The steps involved in agglomerative hierarchical clustering…

* Initialization: Each data point is considered as an individual cluster.

* Distance Calculation: A distance metric, often Euclidean distance, is used to compute the similarity or dissimilarity between clusters. Various distance metrics can be chosen based on the nature of the data.

* Cluster Merging: The two closest clusters are merged into a single cluster, reducing the total number of clusters by one.

* Update Distance Matrix: The distance matrix is updated to reflect the distances between the new merged cluster and the remaining clusters.

* Repeat merging until all data points belong to a single cluster.

Advantages: clear hierarchical representation, no need for prespecified number of clusters, and visual insight such as via dendrogram visualization.

Disadvantages: computational complexity, sensitive to noise, and memory-intensive.
