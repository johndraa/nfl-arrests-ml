# NFL Game Arrest Prediction Project

This project analyzes historical NFL game data to identify factors associated with fan arrest levels and builds machine learning models to predict arrest risk categories for games.

The work was completed as a final project for a university data science course and demonstrates practical experience in data cleaning, feature engineering, exploratory analysis, and model training.

## Project Goal
The goal of this project is to determine whether game context—such as rivalry matchups, score differences, and game outcomes—can help predict whether a game will have low, medium, or high arrest counts.

## Dataset
The dataset contains NFL game arrest data from 2011–2015, with each record representing a single game. Key variables include:

- Teams playing
- Game scores
- Overtime indicator
- Division/rivalry flags
- Number of fan arrests

Dataset source:
https://www.kaggle.com/datasets/washingtonpost/nfl-arrests

## Methods Used
The project involved:

- Data cleaning and preprocessing
- Handling missing and duplicate data
- Feature engineering (score difference, rivalry indicators, etc.)
- Exploratory data analysis and visualization
- Classification model training and comparison

Models evaluated include:
- Logistic Regression
- Random Forest
- XGBoost (best performing model)

## Results
Results show that arrest levels can be partially predicted using game context, with factors such as rivalry games, close score margins, and away team wins correlating with higher arrest counts.

## Technologies Used
- Python
- Pandas
- NumPy
- scikit-learn
- XGBoost
- Jupyter Notebook
- Matplotlib / Seaborn

## Repository Contents
- Jupyter Notebook containing full analysis and modeling workflow
- Project presentation slides
- Supporting scripts and files

## Notes
This repository is maintained as a portfolio project and is not intended for production use. Dataset redistribution may be subject to Kaggle terms of use.
