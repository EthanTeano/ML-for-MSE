# Band Gap Prediction for Binary Semiconductors (SVR + Bayesian Optimization)

This project explores machine learning approaches for predicting the
electronic band gap of binary semiconductor materials using classical
regression models.

The work focuses on feature-based learning using materials descriptors,
with support vector regression (SVR) as the primary model and Bayesian
optimization for hyperparameter tuning.

## Motivation
Accurate band gap prediction is critical for semiconductor device design.
While first-principles methods such as DFT are widely used, they are
computationally expensive and often underestimate band gaps. Machine
learning provides a fast alternative for screening candidate materials.

## Approach
- Descriptor-based feature engineering for binary semiconductors
- Support Vector Regression (SVR)
- Bayesian optimization for hyperparameter selection
- Cross-validation for performance evaluation

## Data
- Binary semiconductor compounds
- Materials descriptors derived from Materials Project entries
- Band gap values obtained from DFT calculations

## Scope
- Learning-focused implementation of classical ML methods
- Emphasis on model behavior, feature importance, and optimization strategy
- Not intended as a state-of-the-art benchmark study

## Status
Completed as a learning and comparison exercise
