# Basics of Reinforcement Learning (RL)

This repository is dedicated to reinforcing the understanding of the basics of Reinforcement Learning (RL), a specialized area within the realm of Artificial Intelligence (AI). RL represents a unique learning paradigm where an intelligent agent learns to make decisions by interacting with its environment, taking actions that are rewarded or penalized. The aim is to maximize cumulative rewards over time. The repository includes comprehensive content, from introductory topics like Markov Decision Processes (MDPs), Policy and Value Iteration, and Q-Learning, to more advanced themes like Deep Q-Learning and Policy Gradient Methods. Suitable for beginners in the field or more experienced learners seeking a refresh It is a valuable resource for anyone interested in understanding the core mechanisms that underpin this fascinating field of study.

# Notebooks Description

* `1_markov_process.ipynb` - This notebook introduces the fundamental concept of Markov Processes. It provides detailed explanations on state transitions and how probabilities play a key role in decision-making. It showcases how to define and work with simple Markov Chains using illustrative examples and Python code.

* `2_markov_reward_process.ipynb` - Building upon the Markov Process concept, this notebook integrates the idea of rewards to form Markov Reward Processes. It discusses the computation of expected rewards and dives into the significance of discount factors in long-term reward predictions.

* `3_markov_decision_process.ipynb` - This notebook explains the Markov Decision Process (MDP) framework, the cornerstone of Reinforcement Learning. It expands on Markov Reward Processes by incorporating actions that the agent can perform. Topics include policy evaluation and policy improvement.

* `4_dynamic_programming.ipynb` - This notebook elucidates the principles of dynamic programming, particularly Value Iteration and Policy Iteration. Through Python examples, it demonstrates how these techniques solve MDPs, providing optimal policies and value functions.

* `5_montecarlo.ipynb` - This notebook offers a practical insight into Monte Carlo Methods, useful for handling problems with large state spaces. It explains both prediction and control aspects of these methods, focusing on exploring how Monte Carlo can be used to estimate value functions and derive optimal policies.

* `6_q_learning.ipynb` - This notebook elaborates on Q-Learning, a popular off-policy algorithm in Reinforcement Learning. It demonstrates the learning of action-value functions, the balance between exploration and exploitation, and how to converge to the optimal policy.

* `7_deep_q_learning.ipynb` - This notebook delves into Deep Q-Learning, an extension of Q-learning which uses deep neural networks as function approximators. It discusses key aspects like Experience Replay, illustrating how to implement Deep Q-Learning to tackle more complex problems.

* `8_reinforce.ipynb` - The final notebook in this series explores Policy Gradient methods, specifically the REINFORCE algorithm. It showcases how to update policies directly using gradient ascent, providing in-depth understanding of the underpinnings of policy-based methods in Reinforcement Learning.

# Installation

1. Clone this repository:
```
git clone https://github.com/sergiorozada12/rl-basics.git
```
2. Navigate to the repository:
```
cd rl-basics
```
3. Install the required packages:
```
pip install -r requirements.txt
```