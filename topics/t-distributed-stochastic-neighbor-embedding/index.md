# t-Distributed Stochastic Neighbor Embedding (t-SNE)

t-Distributed Stochastic Neighbor Embedding (t-SNE) is a dimensionality reduction technique that emphasizes preserving the pairwise similarities between data points. Unlike some other dimensionality reduction techniques (such as prinicpal component analysis), t-SNE focuses on preserving local relationships.

Here's how it works…

Similarity Computation: For each data point in the high-dimensional space, t-SNE computes the pairwise similarity (usually using a Gaussian kernel) between that point and all other points.

Probability Distributions: t-SNE converts the similarities into conditional probabilities that measure the likelihood of choosing one data point as a neighbor given another data point as a reference.

Lower-Dimensional Mapping: t-SNE constructs a lower-dimensional space (typically 2D or 3D) and assigns an initial random position to each data point in that space.

Gradient Descent: t-SNE uses gradient descent optimization to iteratively move the points in the lower-dimensional space so that the pairwise similarity distributions better match the high-dimensional similarity distributions. Points that have high similarities in the high-dimensional space are attracted to each other in the lower-dimensional space, and points with low similarities are repelled from each other.

Limitations: t-SNE is computationally expensive and can be slow for large datasets. It's not suited for reconstructing the original data or for making predictions. Different runs of t-SNE with the same data might yield different results due to the stochastic nature of the algorithm.
