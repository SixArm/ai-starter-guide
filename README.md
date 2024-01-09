# AI Starter Guide

<img src="README.jpg" alt="splash" style="width: 100%;"/>

AI Starter Guide: this book explains one topic at a time, like a big glossary, easy wiki, quick encyclopedia, or summary notes.

* Download the free e-book file [EPUB](ai-starter-guide.epub) or [PDF](ai-starter-guide.pdf).
* If you wish, [pay what you want](https://gumroad.com/l/ai-starter-guide).
* Edited by [Joel Parker Henderson](https://github.com/joelparkerhenderson).
* For questions and suggestions [email me](mailto:joel@joelparkerhenderson.com).

## Contents

### [Introduction](topics/ai-starter-guide-introduction)

### [Artificial intelligence](topics/artificial-intelligence)

* [Artificial General Intelligence (AGI)](topics/artificial-general-intelligence)
* [Artificial Super Intelligence (ASI)](topics/artificial-super-intelligence)
* [Natural language processing (NLP)](topics/natural-language-processing)
* [Explainable Artificial Intelligence (XAI)](topics/explainable-artificial-intelligence)
* [Symbolic artificial intelligence](topics/symbolic-artificial-intelligence)
* [Generative artificial intelligence](topics/generative-artificial-intelligence)
* [Expert system](topics/expert-system)
* [Case-based reasoning (CBR)](topics/case-based-reasoning)

## [AI agent](topics/ai-agent)

* [AI alignment](topics/ai-alignment)
* [AI ethics](topics/ai-ethics)
* [Chain of thought](topics/chain-of-thought)
* [AI hallucination](topics/ai-hallucination)
* [Chatbot](topics/chatbot)


### TODO

* [Machine learning parameters](topics/machine-learning-parameters)
* [Machine learning hyperparameters](topics/machine-learning-hyperparameters)
* [Hyperparameter tuning](topics/hyperparameter-tuning)

### TODO

* [Neural Radiance Fields (NeRF)](topics/neural-radiance-fields)
* [Epsilon-greedy exploration](topics/epsilon-greedy-exploration)
* [Double descent](topics/double-descent)
  
### [AI datasets](topics/ai-datasets)

* [Training data](topics/training-data)
* [Validation data](topics/validation-data)
* [Test data](topics/test-data)

### [Computer processors](topics/computer-processors)

* [Central Processing Unit (CPU)](topics/central-processing-unit)
* [Graphics Processing Unit (GPU)](topics/graphics-processing-unit)
* [Tensor Processing Unit (TPU)](topics/tensor-processing-unit)
* [Vision Processing Unit (VPU)](topics/vision-processing-unit)
* [AI processor](topics/ai-processor)
* [Field Programmable Gate Array (FPGA)](topics/field-programmable-gate-array)

### [Machine learning](topics/machine-learning)

* [Supervised learning](topics/supervised-learning)
* [Unsupervised learning](topics/unsupervised-learning)
* [Reinforcement learning](topics/reinforcement-learning)
* [Deep learning](topics/deep-learning)
* [Backpropagation](topics/backpropagation)
* [Forward Propagation](topics/forward-propagation)
* [Gradient descent](topics/gradient-descent)
* [Zero-shot learning](topics/zero-shot-learning)
* [Hidden Markov Model (HMM)](topics/hidden-markov-model)
* Markov Decision Processes (MDPs)
* Expectation-Maximization (EM) algorithm

### [Machine learning algorithms](topics/machine-learning-algorithms)

* [Decision tree](topics/decision-tree)
* Eager learning algorithms - TODO
* [Lazy learning algorithms](topics/lazy-learning-algorithms)
* Instance-based learning algorithms → lazy learning algorithms
* Memory-based learning algorithms → lazy learning algorithms

### [Supervised learning algorithms](topics/supervised-learning-algorithms)

* [Support Vector Machine (SVM)](topics/support-vector-machine)
* Linear Regression: Used for predicting continuous numerical values.
* Logistic Regression: Used for binary classification problems.
* Decision Trees: Tree-based models for both classification and regression tasks.
* Random Forest: An ensemble method combining multiple decision trees.

### [Unsupervised learning algorithms](topics/unsupervised-learning-algorithms)

* [Self-Organizing Maps (SOM)](topics/self-organizing-maps)
* Kohonen maps → Self-Organizing Maps (SOM)

### [Clustering algorithms](topics/clustering-algorithms)

* K-means Clustering: Partition data points into k clusters based on their proximity to cluster centroids.
* [Hierarchical clustering](topics/hierarchical-clustering)

### [Dimensionality reduction algorithms](topics/dimensionality-reduction-algorithms)

* [Principal Component Analysis (PCA)](topics/principal-component-analysis)
* [t-Distributed Stochastic Neighbor Embedding (t-SNE)](topics/t-distributed-stochastic-neighbor-embedding)

### [Anomaly detection algorithms](topics/anomaly-detection-algorithms)

Statistical Methods:

* [Modified Z-Score](topics/modified-z-score)
* Z-Score
* Percentile: This method identifies anomalies based on percentiles or quantiles of the data distribution.

Density-Based Methods:

* [Local Outlier Factor (LOF)](topics/local-outlier-factor)
* Isolation Forest
* Density-Based Spatial Clustering of Applications with Noise (DBSCAN)

Proximity-Based Methods:

* [k-Nearest Neighbors (KNN)](topics/k-nearest-neighbors)
* Distance-Based Outlier Detection (LOCI)

Machine Learning-Based Methods:

* [Autoencoders](topics/autoencoders)
* One-Class Support Vector Machines (One-Class SVM)

Ensemble Methods:

* [Majority voting](topics/majority-voting)
* Isolation Forest Ensemble

### [Generative models](topics/generative-models)

* Gaussian Mixture Models (GMM): Model a combination of distributions, allowing data generation and density estimation.
* Autoencoders: Neural networks used for unsupervised feature learning.
* Variational Autoencoders (VAE): Learn to generate new data samples by mapping them to a latent space.

## Reinforcement

### [Reinforcement Learning Algorithms](topics/reinforcement-learning-algorithms)

* [Q-Learning](topics/q-learning)
* [Deep Q Networks (DQN)](topics/deep-q-networks)
  * Double Q-learning 
  * Dueling DQNs
  * Rainbow DQN
* [Policy gradient methods](topics/policy-gradient-methods)
* [Deep Deterministic Policy Gradients (DDPG)](topics/deep-deterministic-policy-gradients)
* [Actor-critic](topics/actor-critic)
  
### Semi-supervised learning algorithms

These algorithms leverage both labeled and unlabeled data for learning. They aim to improve model performance by incorporating additional information from unlabeled data. Examples include:

### Self-training

Uses a model to generate pseudo-labeled data from unlabeled examples for further training.

### [Transfer learning algorithms](topics/transfer-learning-algorithms)


### [Ensemble learning algorithms](topics/ensemble-learning-algorithms)

* Bagging (a.k.a. Bootstrap Aggregating)
* [Random forest](topics/random-forest)
* Boosting
* [Gradient Boosting Machines (GBM)](topics/gradient-boosting-machines)
* Extreme Gradient Boosting (XGBoost)
* LightGBM
* [Stacking (a.k.a. Stacked Generalization)](topics/stacking)
* Voting Classifiers (a.k.a. Voting Ensembles)

### Unsupervised learning tasks

* Clustering
* [Dimensionality reduction](topics/dimensionality-reduction)
* [Anomaly detection](topics/anomaly-detection)
* [Density estimation](topics/density-estimation)
* Outlier detection -> anomaly detection
* [Parzen window](topics/parzen-window)
  
## [Large Language Model (LLM)](topics/large-language-model)

* [Generative Pretrained Transformer (GPT)](topics/generative-pretrained-transformer)
* [Contrastive Language-Image Pretraining (CLIP)](topics/contrastive-language-image-pretraining)

### [Neural Network (NN)](topics/neural-network)

* [Convolutional Neural Network (CNN)](topics/convolutional-neural-network)
* [General Adversarial Network (GAN)](topics/general-adversarial-network)
* [Recurrent Neural Network (RNN)](topics/recurrent-neural-network)
* [Deep Neural Network (DNN)](topics/deep-neural-network)
* [Transformer architecture](topics/transformer-architecture)

### [Activation function](topics/activation-function)

* [Hyperbolic Tangent (tanh) activation function](topics/hyperbolic-tangent-activation-function)
* [Rectified Linear Unit (ReLU) activation function](topics/rectified-linear-unit-activation-function)
  * Leaky Rectified Linear Unit (ReLU) activation function (leaky-rectified-linear-unit-activation-function)
  * Parametric Rectified Linear Unit (ReLU) activation function (parametric-rectified-linear-unit-activation-function)
* Scaled Exponential Linear Unit (SELU) activation function (scaled-exponential-unit-activation-function)
* [Sigmoid activation function](topics/sigmoid-activation-function)

### [Loss function](topics/loss-function)

* [Mean Squared Error (MSE)](topics/mean-squared-error)
* [Mean Absolute Error (MAE)](topics/mean-absolute-error)
* Cost function → Loss function
* Objective function → Loss function
* L1 loss → Mean Absolute Error (MAE)
* L1 norm → Mean Absolute Error (MAE)

### [Kernel trick](topics/kernel-trick)

* [Gaussian kernel](topics/gaussian-kernel)
* linear kernel
* polynomial kernel
* radial basis function (RBF) kernel
* sigmoid kernel

### [Machine learning performance metrics](topics/machine-learning-performance-metrics)

* [Accuracy](topics/machine-learning-accuracy)
* [Precision](topics/machine-learning-precision)
* [True Positive Rate (≡ Sensitivity)](topics/true-positive-rate) 
* [True Negative Rate (≡ Specificity)](topics/true-negative-rate)
* F1-Score
* Receiver Operating Characteristic (ROC)
* [Area Under the Curve (AUC)](topics/area-under-the-curve)
* R-squared (R2)
* Silhouette Score
* [Davies-Bouldin Index](topics/davies-bouldin-index)
* Adjusted Rand Index (ARI)
* [Overfitting](topics/overfitting)
* [Underfitting](topics/underfitting)
* Sensitivity → True Positive Rate  
* Specificity → True Negative Rate  
 
### [AI tools](topics/ai-tools)

* [AI content generator](topics/ai-content-generator)
* [AI image generation](topics/ai-image-generation)
* [AI form fill](topics/ai-form-fill)
* [AI UI/UX](topics/ai-ui-ux)
* [AI internationalization/localization](topics/ai-internationalization-localization)
* [AI plagiarism checker](topics/ai-plagiarism-checker)

### [AI for business areas](topics/ai-for-business-areas)

* [AI sales](topics/ai-sales)
* [AI marketing](topics/ai-marketing)
* [AI accounting](topics/ai-accounting)
* [AI human resources](topics/ai-human-resources)
* [AI resource leveling](topics/ai-resource-leveling)
* [AI customer service](topics/ai-customer-service)
* [AI for business strategy](topics/ai-for-business-strategy)
* [AI for change management](topics/ai-for-change-management)
* [AI for partner management](topics/ai-for-partner-management)
* [AI for product development](topics/ai-for-product-development)
* [AI for project management](topics/ai-for-project-management)
* [AI for software programming](topics/ai-for-software-programming)

### [AI + business sectors](topics/ai-plus-business-sectors)

* [AI + adtech (advertising tech)](topics/ai-plus-adtech)
* [AI + agtech (agricultural tech)](topics/ai-plus-agtech)
* [AI + biotech (biological tech)](topics/ai-plus-biotech)
* [AI + cleantech (clean energy tech)](topics/ai-plus-cleantech)
* [AI + edtech (educational tech)](topics/ai-plus-edtech)
* [AI + fintech (financial tech)](topics/ai-plus-fintech)
* [AI + govtech (governmental tech)](topics/ai-plus-govtech)
* [AI + legtech (legal tech)](topics/ai-plus-legtech)
* [AI + martech (marketing tech)](topics/ai-plus-martech)
* [AI + medtech (medical tech)](topics/ai-plus-medtech)
* [AI + realtech (real estate tech)](topics/ai-plus-realtech)
* [AI + regtech (regulatory tech)](topics/ai-plus-regtech)

### [Conclusion](topics/ai-starter-guide-conclusion)

* [About the editor](topics/about-the-editor)
* [About the AI](topics/about-the-ai)
* [About the ebook](topics/about-the-ebook-pdf)
* [About related projects](topics/about-related-projects)

## All our guides

* [Innovation Partnership Guide](https://github.com/sixarm/innovation-partnership-guide)
* [Startup Business Guide](https://github.com/sixarm/startup-business-guide)
* [Business Lingo Guide](https://github.com/sixarm/business-lingo-guide)
* [Project Management Guide](https://github.com/sixarm/project-management-guide)
* [UI/UX Design Guide](https://github.com/sixarm/ui-ux-design-guide)
* [Software Programming Guide](https://github.com/sixarm/software-programming-guide)
* [AI Starter Guide](https://github.com/sixarm/ai-starter-guide)
