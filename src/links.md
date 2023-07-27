### [Introduction](ai-starter-guide-introduction)

### [Artificial intelligence](artificial-intelligence)

* [Artificial General Intelligence (AGI)](artificial-general-intelligence)
* [Artificial Super Intelligence (ASI)](artificial-super-intelligence)
* [Natural language processing (NLP)](natural-language-processing)
* [Explainable Artificial Intelligence (XAI)](explainable-artificial-intelligence)
* [Symbolic artificial intelligence](symbolic-artificial-intelligence)
* [Expert system](expert-system)
  
### TODO

* [AI agent](ai-agent)
* [AI alignment](ai-alignment)
* [AI ethics](ai-ethics)
* [Chain of thought](chain-of-thought)
* [AI hallucination](ai-hallucination)
* [Chatbot](chatbot)
* [Neural Radiance Fields (NeRF)](neural-radiance-fields)
* [Hyperparameter tuning](hyperparameter-tuning)
* [Machine learning parameters](machine-learning-parameters)
* dendrogram

### [AI datasets](ai-datasets)

* [Training data](training-data)
* [Validation data](validation-data)
* [Test data](test-data)

### [Computer processors](computer-processors)

* [Central Processing Unit (CPU)](central-processing-unit)
* [Graphics Processing Unit (GPU)](graphics-processing-unit)
* [Tensor Processing Unit (TPU)](tensor-processing-unit)
* [Vision Processing Unit (VPU)](vision-processing-unit)
* [AI processor](ai-processor)
* Field Programmable Gate Array (FPGA)

### [Machine learning](machine-learning)

* [Supervised learning](supervised-learning)
* [Unsupervised learning](unsupervised-learning)
* [Reinforcement learning](reinforcement-learning)
* [Deep learning](deep-learning)
* [Backpropagation](backpropagation)
* [Forward Propagation](forward-propagation)
* [Gradient descent](gradient-descent)
* [Zero-shot learning](zero-shot-learning)
* [Hidden Markov Model (HMM)](hidden-markov-model)

### [Machine learning algorithms](machine-learning-algorithms)

* [Decision Tree](decision-tree)
* instance-based learning
* lazy learning algorithms

## Supervised

### [Supervised learning algorithms](supervised-learning-algorithms)

* [Support Vector Machine (SVM)](support-vector-machine)
* Linear Regression: Used for predicting continuous numerical values.
* Logistic Regression: Used for binary classification problems.
* Decision Trees: Tree-based models for both classification and regression tasks.
* Random Forest: An ensemble method combining multiple decision trees.

## Unsupervised

### [Unsupervised learning algorithms](unsupervised-learning-algorithms)

* [Self-Organizing Maps (SOM)](self-organizing-maps)
* Kohonen maps → Self-Organizing Maps (SOM)

### [Clustering algorithms](clustering-algorithms)

* K-means Clustering: Partition data points into k clusters based on their proximity to cluster centroids.

* [Hierarchical clustering](hierarchical-clustering)

### [Dimensionality reduction algorithms](dimensionality-reduction-algorithms)

* [Principal Component Analysis (PCA)](principal-component-analysis)
* t-Distributed Stochastic Neighbor Embedding (t-SNE)

### [Anomaly detection algorithms](anomaly-detection-algorithms)

Statistical Methods:

* [Modified Z-Score](modified-z-score)
* Z-Score
* Percentile: This method identifies anomalies based on percentiles or quantiles of the data distribution.

Density-Based Methods:

* [Local Outlier Factor (LOF)](local-outlier-factor)
* Isolation Forest
* Density-Based Spatial Clustering of Applications with Noise (DBSCAN)

Proximity-Based Methods:

* [k-Nearest Neighbors (KNN)](k-nearest-neighbors)
* Distance-Based Outlier Detection (LOCI)

Machine Learning-Based Methods:

* [Autoencoders](autoencoders)
* One-Class Support Vector Machines (One-Class SVM)

Ensemble Methods:

* [Majority voting](majority-voting)
* Isolation Forest Ensemble


### [Generative models](generative-models)

* Gaussian Mixture Models (GMM): Model a combination of distributions, allowing data generation and density estimation.
* Autoencoders: Neural networks used for unsupervised feature learning.
* Variational Autoencoders (VAE): Learn to generate new data samples by mapping them to a latent space.


## Reinforcement

### [Reinforcement Learning Algorithms](reinforcement-learning-algorithms)

* Q-Learning: A model-free algorithm that uses a Q-value function to estimate the expected cumulative reward for taking a particular action in a given state.

* Deep Q Networks (DQN): An extension of Q-learning that uses deep neural networks to approximate the Q-value function, enabling it to handle high-dimensional state spaces.

* Policy Gradient Methods: These algorithms directly optimize the policy to find the best actions, often using techniques like the REINFORCE algorithm or the Proximal Policy Optimization (PPO) algorithm.

* Deep Deterministic Policy Gradients (DDPG): An off-policy algorithm suitable for continuous action spaces, often used in robotic control tasks.

* Actor-Critic: A hybrid algorithm that combines elements of policy-based and value-based methods, using an actor to select actions and a critic to estimate the value of different actions.

### Semi-supervised learning algorithms

These algorithms leverage both labeled and unlabeled data for learning. They aim to improve model performance by incorporating additional information from unlabeled data. Examples include:

### Self-training

Uses a model to generate pseudo-labeled data from unlabeled examples for further training.

### [Transfer learning algorithms](transfer-learning-algorithms)


### [Ensemble learning algorithms](ensemble-learning-algorithms)

* Bagging (a.k.a. Bootstrap Aggregating)
* Random Forest
* Boosting
* Gradient Boosting Machines (GBM)
* Extreme Gradient Boosting (XGBoost)
* LightGBM
* Stacking (a.k.a. Stacked Generalization)
* Voting Classifiers (a.k.a. Voting Ensembles)

### Unsupervised learning tasks

* Clustering
* Dimensionality Reduction
* Anomaly Detection
* Density Estimation

## [Large Language Model (LLM)](large-language-model)

* [Generative Pretrained Transformer (GPT)](generative-pretrained-transformer)
* [Contrastive Language-Image Pretraining (CLIP)](contrastive-language-image-pretraining)

### [Neural Network (NN)](neural-network)

* [Convolutional Neural Network (CNN)](convolutional-neural-network)
* [General Adversarial Network (GAN)](general-adversarial-network)
* [Recurrent Neural Network (RNN)](recurrent-neural-network)
* [Deep Neural Network (DNN)](deep-neural-network)
* [Transformer architecture](transformer-architecture)

### [Activation function](activation-function)

* [Hyperbolic Tangent (tanh) activation function](hyperbolic-tangent-activation-function)
* [Rectified Linear Unit (ReLU) activation function](rectified-linear-unit-activation-function)
* Leaky Rectified Linear Unit (ReLU) activation function (leaky-rectified-linear-unit-activation-function)
* Parametric Rectified Linear Unit (ReLU) activation function (parametric-rectified-linear-unit-activation-function)
* Scaled Exponential Linear Unit (SELU) activation function (scaled-exponential-unit-activation-function)
* [Sigmoid activation function](sigmoid-activation-function)

### [Loss function](loss-function)

* [Mean Squared Error (MSE)](mean-squared-error)
* [Mean Absolute Error (MAE)](mean-absolute-error)
* Cost function → Loss function
* Objective function → Loss function
* L1 loss → Mean Absolute Error (MAE)
* L1 norm → Mean Absolute Error (MAE)

### [Kernel trick](kernel-trick)

* linear kernel
* polynomial kernel
* radial basis function (RBF) kernel
* sigmoid kernel

### [Machine learning performance metrics](machine-learning-performance-metrics)

* [Accuracy](machine-learning-accuracy)
* [Precision](machine-learning-precision)
* Recall (≡ True Positive Rate, Sensitivity)
* Specificity (≡ True Negative Rate)
* F1-Score
* Receiver Operating Characteristic (ROC)
* [Area Under the Curve (AUC)](area-under-the-curve)
* R-squared (R2)
* Silhouette Score
* [Davies-Bouldin Index](davies-bouldin-index)
* Adjusted Rand Index (ARI)
* [Overfitting](overfitting)
* [Underfitting](underfitting)
* True Positive Rate → Recall
* True Negative Rate → Specificity

### [AI tools](ai-tools)

* [AI content generator](ai-content-generator)
* [AI image generation](ai-image-generation)
* [AI form fill](ai-form-fill)
* [AI UI/UX](ai-ui-ux)
* [AI internationalization/localization](ai-internationalization-localization)
* [AI plagiarism checker](ai-plagiarism-checker)

### [AI for business areas](ai-for-business-areas)

* [AI sales](ai-sales)
* [AI marketing](ai-marketing)
* [AI accounting](ai-accounting)
* [AI human resources](ai-human-resources)
* [AI resource leveling](ai-resource-leveling)
* [AI customer service](ai-customer-service)
* [AI for business strategy](ai-for-business-strategy)
* [AI for partner management](ai-for-partner-management)
* [AI for product development](ai-for-product-development)
* [AI for project management](ai-for-project-management)
* [AI for software programming](ai-for-software-programming)

### [AI + business sectors](ai-plus-business-sectors)

* [AI + adtech (advertising tech)](ai-plus-adtech)
* [AI + agtech (agricultural tech)](ai-plus-agtech)
* [AI + biotech (biological tech)](ai-plus-biotech)
* [AI + cleantech (clean energy tech)](ai-plus-cleantech)
* [AI + edtech (educational tech)](ai-plus-edtech)
* [AI + fintech (financial tech)](ai-plus-fintech)
* [AI + govtech (governmental tech)](ai-plus-govtech)
* [AI + legtech (legal tech)](ai-plus-legtech)
* [AI + martech (marketing tech)](ai-plus-martech)
* [AI + medtech (medical tech)](ai-plus-medtech)
* [AI + realtech (real estate tech)](ai-plus-realtech)
* [AI + regtech (regulatory tech)](ai-plus-regtech)

### [Conclusion](ai-starter-guide-conclusion)

* [About the editor](about-the-editor)
* [About the AI](about-the-ai)
* [About the ebook](about-the-ebook-pdf)
* [About related projects](about-related-projects)
