### Overview
This Repository contains my notes from the course **"Introduction to Reinforcement Learning"** taught by David Silver at DeepMind. I have also implemented some of the algorithms along the way.<br/>
Lecture notes are based on one lecture of the online course plus one or more chapters from Sutton and Barto.

### Resources
**Online Course:** [David Silver's Reinforcement Learning Course](https://www.davidsilver.uk/teaching/)<br/>
**Textbook:** [Reinforcement Learning: An Introduction (2nd Edition)](http://incompleteideas.net/book/RLbook2018.pdf)

### Notes Details
#### Lecture-1
- Based on Lecture-1 of the course and Chapter-1 of Sutton and Barto
- This set of notes discusses the problem of Reinforcement Learning and how it differs from other Machine Learning categories such as supervised learning and unsupervised learning
- We also describe some of the terminology used in RL, such as environment, agent, reward, value, model
- Then a brief discussion on exploration-exploitation tradeoff is provided
- This secion of notes is based on

#### Lecture-2
- Based on Lecture-2 of the course and Chapter-3 of Sutton and Barto
- This set of notes talks about the concept of Markov Decision Process (MDP), that most of the RL algorithms are based on
- We also see agent-environment interface
- We understand the concept of policy, return, value functions
- I have also included some of the example from Sutton and Barto to solidify the concepts, as well as solutions of some in-chapter excercise problems
- These notes also talk about Bellman Expectation Equations
- Finally we learn about Bellman Optimality Equations and Optimal Policy

#### Lecture-3
- Based on Lecture-3 of the course and Chapter-4 of Sutton and Barto
- Discusses Dynamic Programming methods to solve the problem of Reinforcement Learning
- Methods such as Policy Evaluation, Policy Improvement, Policy Iteration and Value Iteration are discussed
- We also learn about Synchronous Dynamic Programming and Asynchronous Dynamic Programming methods
- I missed adding bootstrapping to the notes. Many DP methods update estimates of values of states based on estimates of values of successor states. That is they **update estimates based on other estimates**. This general idea is known as **bootstrapping**.

**NOTE: This is a work in progress. This repo will updated soon.**
