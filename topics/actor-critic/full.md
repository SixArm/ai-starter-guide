# Actor-Critic

Actor-Critic is a class of reinforcement learning algorithms that combines elements of both value-based methods and policy-based methods. Actor-Critic methods are known for their stability and efficiency in handling high-dimensional state and action spaces. They have been successfully applied in various domains, including robotics, game playing, and continuous control tasks. The combination of an actor for policy and a critic for value estimation allows for effective learning in complex and dynamic environments.

The actor is responsible for selecting actions based on the current policy. It directly interacts with the environment, proposing actions according to the current policy. The policy defines the probability distribution over actions given a state.

The critic evaluates the actions taken by the actor. It estimates the value function, which represents the expected cumulative reward of following a particular policy. The critic provides feedback to the actor by assessing the quality of the selected actions.

The key idea behind Actor-Critic methods is to leverage the advantages of both policy-based and value-based approaches:

* **Policy-Based (Actor)**: The actor explores and exploits the environment by selecting actions based on the current policy. This introduces a level of stochasticity in the agent's behavior.

* **Value-Based (Critic)**: The critic evaluates the chosen actions, providing a measure of the expected cumulative reward. This evaluation helps guide the actor towards actions that are likely to result in higher rewards.

The Actor-Critic algorithm involves updating both the actor's policy and the critic's value function iteratively. The updates are typically performed using policy gradients for the actor and temporal difference (TD) learning for the critic.

Common Actor-Critic algorithms include:

* **Advantage Actor-Critic (A2C)**: A2C is a synchronous version of the Actor-Critic algorithm. It updates the policy and the value function at each time step, using the advantage function to reduce variance.

* **Asynchronous Advantage Actor-Critic (A3C)**: A3C is an asynchronous version of A2C. It uses multiple parallel actor-learner agents to explore and update the policy and value function asynchronously.

* **Deep Deterministic Policy Gradients (DDPG)**: DDPG is an off-policy Actor-Critic algorithm designed for continuous action spaces. It uses a deterministic policy for continuous actions.

* **Trust Region Policy Optimization (TRPO) and Proximal Policy Optimization (PPO)**: TRPO and PPO are policy optimization algorithms that can be considered as a type of Actor-Critic method. They use a policy gradient approach for updating the actor.

