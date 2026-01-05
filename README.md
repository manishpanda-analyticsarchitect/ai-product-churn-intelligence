# AI-Driven Product Churn Intelligence

## Overview
This project demonstrates how product usage data can be operationalized into
an explainable churn prediction system for B2B SaaS products.

The focus is on business interpretability, decision support, and practical
deployment — not black-box model accuracy.

## Problem Statement
B2B SaaS companies often detect churn too late, after engagement has already
collapsed. This project builds an early-warning churn signal using product
usage behavior.

## Data Signals Used
- Active days in last period
- Number of active users
- Breadth of feature usage
- Engagement score

## Model Approach
- Logistic Regression (chosen for explainability)
- Stratified train/test split
- Probability-based churn risk scoring

## Outputs
- Binary churn prediction
- Churn probability score
- Risk bands (Low / Medium / High)
- Feature-level explainability

## Why This Matters
This system enables Product Ops and Customer Success teams to:
- Proactively identify at-risk accounts
- Understand *why* an account is risky
- Take targeted intervention actions

## Tech Stack
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Future Enhancements
- Time-series feature windows
- Survival analysis
- Integration with Product Analytics tools (Pendo / Gainsight)
