# Band Gap Prediction for Binary Semiconductors  
**SVR + Bayesian Optimization**

This project presents an original, learning-focused implementation of
classical machine learning methods for predicting the electronic band gap
of binary semiconductor materials.

The work explores descriptor-based feature engineering combined with
support vector regression (SVR), with Bayesian optimization used for
systematic hyperparameter tuning.

---

## Motivation
The electronic band gap is a fundamental materials property that governs
the suitability of semiconductors for electronic and optoelectronic
applications. While first-principles methods such as density functional
theory (DFT) are widely used to compute band gaps, they are computationally
expensive and often exhibit systematic underestimation.

Machine learning offers a fast alternative for screening and trend
analysis across large chemical spaces, particularly when combined with
physically motivated materials descriptors.

---

## Approach
- Descriptor-based feature engineering for binary semiconductor compounds
- Support Vector Regression (SVR) for nonlinear regression
- Bayesian optimization for hyperparameter selection
- Cross-validation to evaluate generalization performance

---

## Data
- Binary semiconductor materials
- Materials descriptors generated from crystal structures and elemental
  properties
- Band gap labels derived from Density Functional Theory (DFT) calculations
  sourced from the Materials Project

---

## Scope and Intent
- Independently developed as an original learning and implementation exercise
- Focused on understanding classical ML behavior, feature sensitivity, and
  optimization strategy
- Not intended as a state-of-the-art or benchmark-level study

---

## Key Takeaways
- Classical ML models can capture meaningful trends in semiconductor band gaps
- Feature choice and scaling significantly impact SVR performance
- Bayesian optimization provides a principled alternative to manual
  hyperparameter tuning
-MAE = 0.2eV

---

## Authorship
This project was independently developed by the author. All code was written
from scratch using standard open-source Python libraries.

---

## Status
Completed 





