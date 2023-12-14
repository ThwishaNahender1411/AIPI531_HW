## AIPI Homework 2: Implement double DQN

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

# AIPI Homework 3: Session-Based DRL Recommenders

## Overview
This is part of the AIPI Homework 3, focusing on the development and evaluation of session-based Deep Reinforcement Learning recommenders. The primary goal is to assess the impact of incorporating item features into these recommender systems, especially in the context of e-commerce applications.

## Methodology

Data Preprocessing Steps:

1. Data Merging and Cleaning: The item properties data is concatenated, and the events data is sorted and processed.
2. Feature Extraction and Handling Missing Data: Features like 'categoryid' and 'parentid' are extracted from the item data. Missing items in the events data are identified, and their missing values are handled.
3. One-Hot Encoding: Item features are transformed using one-hot encoding, converting categorical data into a format suitable for machine learning models.

DRL Models Implemented:

1. Feature Engineering: The project involves extracting and processing item-related features from the datasets.
2. One-Hot Encoding for Categorical Features: Incorporate categorical item features into the model.
3. DRL Models: The item features, once processed and encoded, are used as input to the DRL models.

## Conclusion
Successfully trained and compared session-based DRL recommenders with and without item features. The inclusion of item features significantly enhances the recommendation performance for e-commerce applications, demonstrating the value of incorporating additional item-level information into the recommendation process.

## Files in the Repository
- `AIPI_HW3.ipynb`: The main Jupyter Notebook containing the executable code and analysis.
- `SA2C.py`, `SA2C_new.py`: Helper scripts for the SA2C model.
- `SNQN.py`, `SNQN_new.py`: Helper scripts for the SNQN model.
- `SNQN_Features.py`, `SNQN_Features_new.py`: Scripts related to the SNQN model with item features.



