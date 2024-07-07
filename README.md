# MountainCar Reinforcement Learning AI Agent

This repository contains the implementation of a Deep Q-Network (DQN) to solve the MountainCar-v0 environment using reinforcement learning. The code is implemented in Python using PyTorch and Gymnasium.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Video Output](#video-output)


## Introduction
The goal of this project is to train an AI agent to drive a car up a steep hill using a Deep Q-Network. The agent interacts with the environment and improves its policy based on the rewards received.

## Installation
To run this project, you need to install the required dependencies. You can do this by running the following commands:

```bash
pip install gymnasium
pip install "gymnasium[atari,accept-rom-license]"
apt-get install -y swig
pip install gymnasium[classic-control]
```
## Usage
To train the AI agent, execute the provided Jupyter Notebook, Or you can open this Google Colab File:
[Google Colab Link](https://colab.research.google.com/drive/12p93xXxSYDMTxjnNW2GwaF3tcvOLAMYa)

The notebook will walk you through the following steps:

* Importing the necessary libraries.
* Defining the neural network architecture.
* Initializing the environment and setting the hyperparameters.
* Implementing the experience replay mechanism.
* Defining the DQN agent.
* Training the agent.
## Results
The DQN agent is trained for a maximum of 2000 episodes or until it reaches an average score of 200 over 100 consecutive episodes. The training progress, including the average score per 100 episodes, is printed during training.

## Video Output
A video demonstration of the trained agent can be generated and viewed. To create the video, the trained agent interacts with the environment, and the frames are saved and compiled into an MP4 file.


https://github.com/Ahmad1015/MountainCar-ReinforcementLearning-AI-Agent/assets/129595472/2e7e54b3-5d7a-4172-b212-c9dc0c52ea7c

