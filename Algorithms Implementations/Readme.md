### Reinforcement Learning Algorithms Implementations
Implementations of common RL algorithms discussed in Sutton and Barto. All the algorithms were implemented and tested on Google Colab.

Each directory contains implementations one or more sets of algorithms based on Sutton (except for "openai_gym_tutorial").

#### openai_gym_tutorial
- Notebook to set up the Gym environment (Resource: https://gym.openai.com/docs/)

#### Dynamic Programming (DP)
- Implementation of following algorithms on Small Gridworld example
  - Policy evaluation
  - Policy improvement and policy iteration
  - Value iteration
- An implementation of Markov Decision Process for Small Gridworld is also provided.

## Monte Carlo (MC)
- Implementation of following algorithms
  - Incremental every-visit MC policy evaluation
  - On-policy control using epsilon-greedy policy evaluation
  - Off-policy control using weighted importance sampling
- Executed algorithms on openai gym's Blackjack environment

## Temporal-Difference (TD)
- Implementation of following algorithms
  - Sarsa
  - Sarsa(lambda) using eligibility traces
  - Q-Learning
- Executed algorithms on openai gym's Blackjack, Cliff-Walking environments
