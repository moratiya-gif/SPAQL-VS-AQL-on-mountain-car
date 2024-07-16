# SPAQL-VS-AQL-on-mountain-car

This project evaluates Q learning 'adaptive Q-learning (AQL) and single-partition adaptive Q-learning (SPAQL) for efficient model-free episodic reinforcement learning (RL) in the Mountain Car problem. AQL dynamically partitions the state-action space of a Markov decision process (MDP) while learning control policies. SPAQL differs by learning time-invariant policies, where the state-action mapping does not depend on the time step. 
The Mountain Car environment presents a challenging task where an underpowered car must learn to climb a steep hill. Each algorithm's performance will be evaluated based on criteria such as convergence speed and maximum cumulative reward.
In our work we based ourselves on the article :"Araujo, J. P., Figueiredo, M. A., & Botto, M. A. (2022). Control with adaptive Q-learning: A comparison for two classical control problems. Engineering Applications of Artificial Intelligence, 112, 104797."

conclusions: 
1. Superior Performance of SPAQL and SPAQL-TS
  - Efficiency: Outperform AQL, particularly in continuous state-action spaces and time-variant problems.
  - Sample Efficiency: Faster convergence to optimal policy and higher cumulative rewards.
2. Explainability and Interpretability
 Rational Decision Making: Clear understanding of the rationality behind decision-making processes.

dependencies:
- gym==0.21.0
- numpy
- torch
- imageio
- matplotlib


References:
- https://github.com/kumarnikhil936/q_learning_mountain_car_openai
- https://github.com/jaraujo98/SinglePartitionAdaptiveQLearning
