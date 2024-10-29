# Powergrid control based on the [grid2op](https://grid2op.readthedocs.io/en/latest/) environment

This project is an implementation of an agent that acts on the powergrid, subject to a number of constraints (i.e. operational rules), with the goal of ensuring a reliable flow of power

## Overview

This project addresses the complexity of managing power grid operations—such as controlling power overflows and preventing cascading failures—by implementing two reinforcement learning algorithms in the _Grid2Op_ environment. The agents are organized in two clearly labeled notebooks. The first agent uses the _Proximal Policy Optimization (PPO)_ algorithm, while the second employs variations of the _Deep Q-Network (DQN)_ algorithm.

### Proximal Policy Optimization

_Proximal Policy Optimization (PPO)_ is a popular reinforcement learning algorithm introduced by OpenAI, designed for training policies in environments with complex action spaces. PPO is an improvement over traditional policy gradient methods, optimizing the policy by iteratively updating it in a way that avoids overly large updates, which can destabilize training.

### Deep Q-Network

_Deep Q-Networks (DQN)_ is a foundational deep reinforcement learning algorithm developed by DeepMind that combines Q-learning with deep neural networks. It is designed to enable agents to learn optimal policies in high-dimensional, complex environments, particularly where the state space is too large for traditional Q-learning.

## Requirements

- python >= 3.10
- stable_baseline3
- numpy
- grid2op
- jupyter
- gymnasium

## Usage

To train the PPO agent simply run all the cells in **the-ppo-agent.ipynb**
To train the QDN agent simply run all the cells in **DQN_Variants.ipynb**

