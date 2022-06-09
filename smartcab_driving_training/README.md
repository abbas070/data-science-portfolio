# Reinforcement Learning
## Project: Train a Smartcab How to Drive

Udacity's Machine Learning Nanodegree program provided the idea for this project. This project also requires **Python 2.7** with the [pygame](https://www.pygame.org/wiki/GettingStarted
) library installed.

### Introduction

In this project, we work towards constructing an optimized Q-Learning driving agent that will navigate a Smartcab through its environment towards a goal. Since the Smartcab is expected to drive passengers from one location to another, the driving agent will be evaluated on two very important metrics: Safety and Reliability. A driving agent that gets the Smartcab to its destination while running red lights or narrowly avoiding accidents would be considered unsafe. Similarly, a driving agent that frequently fails to reach the destination in time would be considered unreliable. Maximizing the driving agent's safety and reliability would ensure that Smartcabs have a permanent place in the transportation industry.

Note that, template code for the Smartcab's environment and other agents (cars) in the environment was already provided. Our job is to implement a learning algorithm so that the Smartcab behaves properly, following the rules and regulations, while moving towards its destination.
