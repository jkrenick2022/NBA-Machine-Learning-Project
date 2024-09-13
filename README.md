# NBA Score Predictions

This project uses historical NBA game data to predict the scores of upcoming games. The project applies machine learning models, specifically a Decision Tree classifier, to predict the final away and home team scores based on various input features such as team names, game dates, and betting data (e.g., line and over/under).

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model](#model)

## Project Overview

The goal of this project is to predict NBA game scores using machine learning techniques. We use historical data for various features, including team names, game dates, betting line, and over/under values, to train the model. 

A Decision Tree classifier is applied to make predictions on a test dataset of upcoming games. The model was built using Python, with libraries such as Pandas for data manipulation and Scikit-learn for building the machine learning model.

## Dataset

The dataset contains the following columns:

- **season**: The NBA season year
- **date**: Date of the game
- **away.team**: The away team name
- **away.score**: The actual score of the away team
- **home.team**: The home team name
- **home.score**: The actual score of the home team
- **line**: The betting line
- **over_under**: The over/under value for the game

## Model

We utilize a **Decision Tree Classifier** from the Scikit-learn library. The model is trained on the historical NBA dataset to predict both the away and home team scores. The categorical variables, such as team names and game dates, are encoded using **LabelEncoder** to be used by the model.
