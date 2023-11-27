# Kernel trick

The kernel trick is a powerful concept used in machine learning, particularly in the context of Support Vector Machines (SVMs) and kernel methods. Many real-world datasets are not linearly separable. The kernel trick circumvents this limitation by defining a kernel function, also known as a kernel. The kernel function calculates the dot product (or a similarity measure) between the original data points in the input space, implicitly transforming the data into a higher-dimensional feature space where it may become linearly separable. This higher-dimensional feature space is called the feature space induced by the kernel.

Function:

* $K(x_i, x_j) = φ(x_i) · φ(x_j)$
* $K(x_i, x_j)$ is the value of the kernel function.
* $x_i$ and $x_j$ are points in the input space
* $φ(.)$ represents the implicit mapping function to the feature space.

The most commonly used kernels include: linear kernal (typically for no transformation), polynomial kernel (typically for polynomial seperable data), and radial basis function (RBF) kernel (typically for non-linearly separable data).

Using the kernel trick, SVMs can efficiently work in the higher-dimensional feature space without explicitly transforming the data. This avoids the computational burden associated with high-dimensional feature spaces and allows SVMs to model complex decision boundaries in the original input space. The kernel trick is a fundamental concept in kernel methods and has applications beyond SVMs, such as kernel-based regression and kernel principal component analysis (PCA).
