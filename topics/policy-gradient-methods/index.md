# Policy gradient methods

Policy gradient methods are a class of reinforcement learning algorithms that directly learn the policy, which is a strategy or a mapping from states to actions, in order to maximize the expected cumulative reward. Unlike value-based methods, which aim to learn the value function (expected cumulative reward) and derive the policy from it, policy gradient methods directly parameterize and optimize the policy.

Policy gradient methods are known for their ability to handle high-dimensional action spaces and stochastic policies. They have been successfully applied in various domains, including robotics, natural language processing, and game playing.

**Key aspects:**

* **Policy (π)**: The policy defines the agent's strategy, specifying the probability distribution over actions given a particular state.

* **Objective Function**: The objective is to maximize the expected cumulative reward. The objective function typically involves taking the gradient of the expected reward with respect to the policy parameters.

* **Policy Gradient**: The policy gradient is the gradient of the expected reward with respect to the policy parameters. It indicates how the policy should be adjusted to increase or decrease the probability of taking certain actions in certain states.

* **Gradient Ascent**: Policy gradient methods use gradient ascent to iteratively update the policy parameters in the direction that increases the expected reward.

* **REINFORCE Algorithm**: REINFORCE (Monte Carlo policy gradient) is a fundamental policy gradient algorithm. It estimates the gradient of the expected reward and updates the policy parameters accordingly.

* **Actor-Critic Methods**: Actor-critic methods combine elements of policy gradient and value-based methods. They have an actor (policy) network and a critic (value) network, where the critic evaluates the value of actions taken by the actor.

* **Entropy Regularization**: Some policy gradient methods include entropy regularization terms to encourage exploration. Entropy is a measure of uncertainty in the policy, and regularization can prevent the policy from becoming overly deterministic.

* **Advantage Function**: The advantage function represents the advantage of taking a particular action in a specific state compared to the expected value. It is often used in policy gradient methods to reduce variance.

Popular policy gradient algorithms include:

* REINFORCE (Vanilla Policy Gradient): A basic policy gradient algorithm.
* Proximal Policy Optimization (PPO): An algorithm that addresses some of the issues with high-variance policy * gradient methods.
* Trust Region Policy Optimization (TRPO): A policy optimization algorithm that seeks to ensure small policy updates * to prevent large policy changes.
