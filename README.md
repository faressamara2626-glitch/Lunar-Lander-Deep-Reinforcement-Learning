# Lunar Lander Deep Reinforcement Learning

## Overview
This project applies deep reinforcement learning to the Gymnasium LunarLander-v3 environment. The goal is to train an intelligent agent to land a lunar module safely while considering fuel as an additional resource feature.

The project compares a Baseline Deep Q-Network (DQN) agent with an Advanced Double DQN (DDQN) agent under the same architecture and hyperparameters

## Project Topic
Intelligent Lunar Landing: Deep Reinforcement Learning with Resource Management

## Environment
The project uses:

- Gymnasium LunarLander-v3
- Box2D environment
- Discrete action space
- Continuous observation space

The original LunarLander observation has 8 features. In this project, an additional normalized fuel feature was added:

```text
fuel_fraction ∈ [0, 1]
