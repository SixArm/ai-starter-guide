# Generative models

Generative models are a class of machine learning models designed to learn and model the underlying distribution of a dataset. These models can generate new data points that resemble the original data and are useful for various tasks, including data synthesis, data augmentation, and generating new samples for creative purposes. 

Some common types…

Variational Autoencoders (VAEs): VAEs learn to encode data into a latent space and then decode it back to reconstruct the original data. VAEs impose constraints on the latent space to follow a specific distribution, usually a Gaussian distribution, enabling the generation of new data.

Generative Adversarial Networks (GANs): GANs consist of two neural networks: a generator creates fakes, and the discriminator tries to detect fakes. Both networks improve iteratively.

Autoregressive Models: These model the probability distribution of a sequence of data by making assumptions about the conditional probability of each data point given its predecessors. 

Normalizing Flows: These are a family of generative models that use invertible transformations to map data from a simple distribution to a more complex distribution.

Generative Moment Matching Networks (GMMNs): GMMNs use moment matching to match the moments of the generated distribution to the moments of the real data distribution. 

Boltzmann Machines: These are a type of energy-based model that learns to capture the distribution of the data in terms of energy levels. They can be used for both generative and discriminative tasks.
