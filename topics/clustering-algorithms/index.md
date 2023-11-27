# Clustering algorithms

Clustering algorithms are unsupervised machine learning techniques that group similar data points together. The goal is to discover inherent structures in the data, without needing any labeled examples.

Some common ones:

* K-Means: Partition the data into K clusters by iteratively updating cluster centers (centroids) and assigning data points to the nearest centroid. 

* Hierarchical Clustering: Build a tree-like hierarchy of clusters. Variations are agglomerative (start with points then merged based on similarity) or divisive (start with clusters then split recursively).

* DBSCAN (Density-Based Spatial Clustering of Applications with Noise): Group data points that are closely packed, and label outliers as noise. This does not require specifying the number of clusters beforehand.

* Mean Shift: Shift data points towards higher-density regions in the feature space. Converge to cluster centroids. Identify clusters of different shapes and sizes.

* Gaussian Mixture Model (GMM): Estimate the parameters of Gaussian distributions to perform clustering, modeling that the data points are generated from a mixture of Gaussian distributions. 

* Affinity Propagation: Find exemplars in the data that best represent other data points. Pass messages between data points to identify exemplars.

* Spectral Clustering: Use spectral properties of the data to create clusters. Transform the data into a lower-dimensional space and then applying traditional clustering algorithms.

* Agglomerative Information Bottleneck: Use information bottleneck theory to perform hierarchical agglomerative clustering by maximizing mutual information between data points and cluster assignments.
