# Student Pass/Fail Prediction using Random Forest

## Overview
This project demonstrates hyperparameter tuning of a Random Forest classifier using GridSearchCV with 5-fold cross-validation.

## Features
- Random Forest Classifier
- GridSearchCV
- 5-Fold Cross Validation
- Weighted F1 Score
- Python Logging
- Experiment Results DataFrame
- Reproducible using random_state=42

## Dataset
A small inlined dataset representing student performance with the following features:
- study_hours
- attendance_pct
- assignments_done

Target:
- pass (1 = Pass, 0 = Fail)

## Hyperparameter Grid
- n_estimators: [10, 50, 100]
- max_depth: [3, 5, 10]

## Evaluation
- Cross-validation scoring: `f1_weighted`
- Test metric: Weighted F1 Score

## How to Run
```bash
pip install -r requirements.txt
python student_rf_gridsearch.py
