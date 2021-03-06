### Overview
This Repository contains my notes from the course **"Introduction to Reinforcement Learning"** taught by David Silver at DeepMind. Implementation of some of the popular reinforcement learning algorithms is also available.<br/>

Lecture notes are primarily based on the course videos, slides and Reinforcemnt Learning textbook by Sutton and Barto mentioned below. All algorithms are implemented in Python3.7.

### Resources
**Online Course:** [David Silver's Reinforcement Learning Course](https://www.davidsilver.uk/teaching/)<br/>
**Textbook:** [Reinforcement Learning: An Introduction (2nd Edition)](http://incompleteideas.net/book/RLbook2018.pdf)

### Lecture Notes details
1. Introduction to reinforcement learning
2. Markov decision processes and Bellman equations
3. Dynamic programming methods for prediction and control
4. Model free prediction - Monte-Carlo and temporal-difference prediction
5. Model free control, Sarsa, Q-learning
6. Value function approximation methods, deep Q-learning (DQN)
7. Policy gradient methods
8. Planning and Learning

### List of Implemented Algorithms
Following algorithms are currently implemented:

- **Dynamic Programming (DP)**
  - Policy evaluation
  - Policy improvement and policy iteration
  - Value iteration

- **Monte Carlo (MC)**
  - Incremental every-visit MC policy evaluation
  - On-policy control using epsilon-greedy policy evaluation
  - Off-policy control using weighted importance sampling

- **Temporal-Difference (TD)**
  - Sarsa
  - Sarsa(lambda) using eligibility traces
  - Q-Learning
  
- **Function Approximation Methods**
  - Semi-gradient Q-learning

- **Deep Q-Networks (DQN)**

- **DQN with Double Q-learning (Double DQN)**

- **Policy Gradient Methods**
  - REINFORCE-with-baseline: Monte-Carlo Policy Gradient
  
- **Dyna-Q algorithm (Planning and Learning)**
