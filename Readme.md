### Overview
This Repository contains my notes from the course **"Introduction to Reinforcement Learning"** taught by David Silver at DeepMind. I have also implemented some of the popular reinforcement learning algorithms.<br/>

Lecture notes are based on one lecture of the online course plus one or more chapters from Sutton and Barto. All algorithms are implemented in Python3.7.

### Resources
**Online Course:** [David Silver's Reinforcement Learning Course](https://www.davidsilver.uk/teaching/)<br/>
**Textbook:** [Reinforcement Learning: An Introduction (2nd Edition)](http://incompleteideas.net/book/RLbook2018.pdf)

### Lecture Notes details
1. Introduction to Reinforcement Learning
2. Markov Decision Processes and Bellman Equations
3. Dynamic Programming
4. Model Free Prediction
    - Monte Carlo prediction
    - Temporal Difference prediction
    - TD-lambda methods
    - Off-policy MC prediction using importance sampling
5. Model Free Control
    - Monte Carlo control
    - On-policy TD control: Sarsa
    - n-step Sarsa and Sarsa(lambda)
    - Q-Learning
6. Function Approximation
    - Incremental VFA methods such as
        - Gradient Monte-Carlo 
        - Semi-gradient temporal difference
        - Semi-gradient Sarsa, Sarsa($lambda$)
    - Batch VFA methods using least squares prediction such as LSTD, LSMC
    - Least squares policy iteration and LSTDQ algorithm
    - Deep Q-learning (DQN) and associated techniques such as experience replay

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
  
**NOTE: This repo will be updated soon with more notes and implementations.**
