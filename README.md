# AIPI Homework 3: Session-Based DRL Recommenders

## Project Overview
This project is part of the AIPI Homework 3, focusing on the development and evaluation of session-based Deep Reinforcement Learning recommenders. The primary goal is to assess the impact of incorporating item features into these recommender systems, especially in the context of e-commerce applications.

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



