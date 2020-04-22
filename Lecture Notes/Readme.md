### Notes Details
Two major resources are used in preparing these notes:
1. Lecture videos and slides from [David Silver's Reinforcement Learning Course](https://www.davidsilver.uk/teaching/)<br/>
2. [Reinforcement Learning: An Introduction (2nd Edition)](http://incompleteideas.net/book/RLbook2018.pdf)

#### 1. Introduction to Reinforcement Learning
- Based on Lecture-1 of the course and Chapter-1 of Sutton and Barto
- This set of notes discusses the problem of Reinforcement Learning and how it differs from other Machine Learning categories such as supervised learning and unsupervised learning
- We also describe some of the terminology used in RL, such as environment, agent, reward, value, model
- Then a brief discussion on exploration-exploitation tradeoff is provided
- This secion of notes is based on

#### 2. Markov Decision Processes and Bellman Equations
- Based on Lecture-2 of the course and Chapter-3 of Sutton and Barto
- This set of notes talks about the concept of Markov Decision Process (MDP), that most of the RL algorithms are based on
- We also see agent-environment interface
- We understand the concept of policy, return, value functions
- I have also included some of the example from Sutton and Barto to solidify the concepts, as well as solutions of some in-chapter excercise problems
- These notes also talk about Bellman Expectation Equations
- Finally we learn about Bellman Optimality Equations and Optimal Policy

#### 3. Dynamic Programming
- Based on Lecture-3 of the course and Chapter-4 of Sutton and Barto
- Discusses Dynamic Programming methods to solve the problem of Reinforcement Learning
- Methods such as Policy Evaluation, Policy Improvement, Policy Iteration and Value Iteration are discussed
- We also learn about Synchronous Dynamic Programming and Asynchronous Dynamic Programming methods

#### 4. Model Free Prediction
- Based on Lecture-4 of the course and Chapters-5,6,7,12 of Sutton and Barto
- These notes talk about the problem of model-free prediction, where the environment of MDP is unknown
- Study Monte Carlo methods for policy evaluation
- Study Temporal Difference methods TD(0)
- Also learn about n-step bootstrapping methods, eligibility traces and TD(lambda) methods for prediction
- Off-policy prediction methods are also covered

#### 5. Model Free Control
- Based on Lecture-5 of the course and Chapters-5,6,7,12 of Sutton and Barto
- These notes talk about the problem of model-free control, where the environment of MDP is unknown
- Study on-policy control methods such as Monte Carlo control, Sarsa
- Also learn about n-step Sarsa and Sarsa(lambda) methods for model-free control
- Off-policy control methods such as MC and Q-learning are also covered
