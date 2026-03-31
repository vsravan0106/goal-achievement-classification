# Goal Achievement Classification Model

A binary classification ML model that predicts whether a person will achieve their goal based on 11 psychological and behavioral features.

## Problem Statement
Goal failure is not random — it is predictable. This project uses machine learning to identify the behavioral patterns that separate people who achieve their goals from those who don't.

## Results
| Model | Accuracy | ROC-AUC |
|---|---|---|
| Logistic Regression | 80% | 0.7852 |
| Decision Tree | 80% | 0.5547 |
| Random Forest | 80% | 0.7500 |

**Best Model: Logistic Regression — Accuracy 80%, ROC-AUC 0.7852**

## Top Finding
Past Success Rate was the #1 most important feature — validating Bandura's Self Efficacy Theory with real data.

## Features Used
- Plan Granularity
- Social Support
- Initial Intensity
- Feedback Frequency
- Identity Congruence
- External Stressors
- Goal Specificity
- Past Success Rate
- Intrinsic Motivation
- Deadline Presence
- Obstacle Anticipation

## Tech Stack
Python · Pandas · Scikit-learn · Seaborn · Matplotlib

## Live Notebook
https://www.kaggle.com/code/sravan0106/goal-achievement-classification
