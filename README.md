# Space-Titanic-classification-model

# Overview

This repository contains the code and data for a machine learning project that predicts which passengers were transported to another dimension in the "Space Titanic" competition. The project demonstrates a complete machine learning pipeline, including data exploration, feature engineering, model training and classification.

# Dataset Description

The dataset (space_titanic_train.csv and space_titanic_test.csv) contains information about passengers on the Space Titanic, including:

PassengerId: Unique identifier for each passenger.
HomePlanet: The planet the passenger is from.
CryoSleep: Indicates whether the passenger elected to be in cryogenic sleep during the voyage.
Cabin: The passenger’s cabin number (may include deck, cabin number, and side).
Destination: The destination planet of the passenger.
Age: The passenger’s age.
VIP: Whether the passenger paid for special VIP services.
RoomService, FoodCourt, ShoppingMall, Spa, VRDeck: Amounts the passenger spent on various onboard amenities.
Name: The passenger’s name.
Transported: Target variable (training set only). Indicates whether the passenger was transported to another dimension (True or False).

# Project Structure

The project is organized as follows:

classification_space_titanic.ipynb: Jupyter Notebook that integrates the entire workflow — from data exploration and feature engineering to model training, evaluation, and prediction.
space_titanic_train.py: Python script that preprocesses the training dataset, performs feature engineering, and trains the classification model.
space_titanic_test.py: Python script that preprocesses the test dataset using the same feature engineering steps to ensure consistency for final predictions.

# Model Overview

* Data Exploration: Visualizing and analyzing the data to identify trends and correlations.
* Feature Engineering: Creating new features and handling missing values to improve model performance.
* Model Training and Evaluation: Training a classification model to predict passenger transport outcomes.
* Prediction Generation: Generating final predictions for the test dataset.
This project is implemented in Python using popular data science libraries, providing a solid foundation for classification modeling tasks.
