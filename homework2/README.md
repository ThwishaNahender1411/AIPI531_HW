# AIPI Homework 2: Implement double DQN

## Overview
This Jupyter Notebook demonstrates the implementation and training of Deep Reinforcement Learning (DRL) models using stable-baselines3. The project is centered around experimenting with DRL in a controlled environment.

## Environment Setup
Installation: The notebook begins by installing necessary packages like ffmpeg, freeglut3-dev, xvfb for visualization, and stable-baselines3 for reinforcement learning.
Library Imports: Essential libraries such as gymnasium, numpy, torch, and matplotlib are imported.

## Experiment Setup
Environment: The DRL environment used is "MountainCar-v0", a classic problem in reinforcement learning. The environment is rendered in RGB array mode for visualizations.
TensorBoard Logging: A directory for TensorBoard logs is set up to monitor training.

## DRL Model
Model Definition: A DQN (Deep Q-Network) model is defined using the MlpPolicy. Key parameters include training frequency, gradient steps, gamma, exploration parameters, target update interval, learning rate, and network architecture.
Model Training: The DQN model is trained with a specified number of steps, and its performance is evaluated periodically.

## Evaluation and Visualization
Performance Metrics: The model's mean reward and standard deviation are computed and printed.
Video Recording and Display: The notebook includes functions to record and display videos of the model's performance in the environment.
