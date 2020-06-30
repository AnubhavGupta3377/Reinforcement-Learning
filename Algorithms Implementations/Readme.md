### Reinforcement Learning Algorithms Implementations
<img src="/images/MountainCar.gif" width="350" height="250"/> <img src="/images/Breakout.gif" width="180" height="250"/> <img src="/images/Pong.gif" width="250" height="250"/>

Implementations of common RL algorithms discussed in Sutton and Barto. All the algorithms were implemented and tested on Google Colab.

Each directory contains implementations one or more sets of algorithms based on Sutton (except for "openai_gym_tutorial").

#### [openai_gym_tutorial](openai_gym_tutorial)
- Notebook to set up the Gym environment (Resource: https://gym.openai.com/docs/)

#### [Dynamic Programming](Dynamic Programming (DP))
- Implementation of following algorithms on Small Gridworld example
  - Policy evaluation
  - Policy improvement and policy iteration
  - Value iteration
- An implementation of Markov Decision Process for Small Gridworld is also provided.

#### [Monte Carlo](Monte Carlo (MC))
- Implementation of following algorithms
  - Incremental every-visit MC policy evaluation
  - On-policy control using epsilon-greedy policy evaluation
  - Off-policy control using weighted importance sampling
- Executed algorithms on openai gym's Blackjack environment

#### [Temporal-Difference](Temporal-Difference (TD))
- Implementation of following algorithms
  - Sarsa
  - Sarsa(lambda) using eligibility traces
  - Q-Learning
- Executed algorithms on openai gym's Blackjack, Cliff-Walking environments

#### [Function Approximation](Function Approximation)
- Implemented semi-gradient Q-learning algorithm
- Executed algorithm on openai gym's MountainCar environment

#### [DQN](DQN)
- Implementation of Deep Q-Networks (DQN)
- Executed on Atari Breakout and Pong environments
- Different variations include:
    - DQN_Pong.ipynb: The first implementation of DQN with frame-skipping
    - DQN_Breakout.ipynb: Includes efficient implementation of replay memory and frame-skipping
- Perfect Score on Pong
- On breakout, average score of 45 and max score of 330 was achieved

#### [Double DQN](Double DQN)
- Implementation of Double DQN
- Executed on Atari Breakout environment
- Efficient implementation of replay memory and frame-skipping
- Average score of 35 was achieved for breakout


#### [Policy Gradient](Policy Gradient)
- Implementation of following algorithms
  - REINFORCE-with-baseline (MC policy gradient)
- Executed algorithm on openai gym's Cliff-Walking environment

#### [Dyna](Dyna)
- Implementation of Dyna-Q algorithm (planning and learning)
- Executed algorithm on openai gym's Cliff-Walking environment
