# NFL Game Arrest Prediction (2011–2015)

## Project Goal
Predict arrest risk levels (Low, Medium, High) at NFL games using game context such as rivalry matchups, score differences, and game outcomes.

## Dataset
NFL fan arrest data (2011–2015) sourced from Kaggle, where each row represents a single NFL game and includes team info, scores, and arrest counts.

## Workflow
Data Cleaning → Exploratory Analysis → Feature Engineering → Model Training → Cross-Validation → Hyperparameter Tuning → Final Evaluation → Ensemble Comparison

## Models Compared
- Logistic Regression
- Random Forest
- XGBoost (baseline + tuned)
- Ensemble model

## Final Result
Tuned XGBoost achieved the best performance (~0.68 accuracy) and handled high-arrest games better than other models.

## Key Findings
- Rivalry games increase arrest risk
- Close games lead to more incidents
- Away team wins correlate with higher arrests
- Certain stadiums consistently show higher arrest counts

## How to Run
```bash
pip install -r requirements.txt

