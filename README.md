# Stock Trading With Reinforcement Learning

## Project Overview

This repository contains code and resources for developing and testing reinforcement learning agents for stock trading, with a focus on Apple stock and include portfolio trading for exploration. The project leverages custom environments, [gym-anytrading](https://github.com/AI4Finance-LLC/gym-anytrading), and [FinRL](https://github.com/AI4Finance-Foundation/FinRL-PyTorch) library. The implemented algorithms include Deep Q-Network (DQN), Proximal Policy Optimization (PPO), Deep Deterministic Policy Gradient (DDPG) and Advantage Actor-Critic (A2C).


## Installation

1. To get started, clone this repository to your local machine:

```bash
git clone https://github.com/zeyuleochen/RL-Trading.git
cd RL-Trading
```
2. To use the FinRL library, install the library with the following commands

```bash
pip install swig
pip install box2d
pip install git+https://github.com/AI4Finance-Foundation/FinRL.git
```
3. To use the Gym-Anytrading library, install the library with the following
```bash
pip install gym-anytrading
```
OR

```bash
git clone https://github.com/AminHP/gym-anytrading
cd gym-anytrading
pip install -e .

## or

pip install --upgrade --no-deps --force-reinstall https://github.com/AminHP/gym-anytrading/archive/master.zip
```

## Contents

Explore the results and notebooks for different components of the project:

1. [**FinRL**](./FinRL)
   - Find results and notebooks related to the FinRL library.

2. [**Custom Environment**](./custom)
   - Access results and notebooks specific to custom environments.

3. [**Gym-anytrading**](./anytrading)
   - Check out results and notebooks associated with the gym-anytrading library.
     
4.  [**Results and Presentation**](./slides)
   - Check out the presentation report for the project

