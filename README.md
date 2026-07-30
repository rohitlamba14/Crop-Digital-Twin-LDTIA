# Crop-Digital-Twin-LDTIA

Implementation of the Lightweight Digital Twin-Inspired Abstraction (LDTIA) framework for interpretable multiclass crop suitability prediction using ensemble learning.

## Overview

This repository contains the implementation accompanying the research paper:

**A Lightweight Digital Twin-Inspired Virtual Abstraction Framework for Interpretable Multiclass Crop Suitability Prediction Using Ensemble Learning**

The proposed framework:
- Generates abstraction-derived crop suitability labels using a lightweight digital twin-inspired rule-based layer.
- Performs domain-specific feature engineering.
- Evaluates Random Forest, Gradient Boosting, and XGBoost classifiers.
- Provides SHAP-based explainability.
- Includes an ablation study.

## Dataset

The Crop Recommendation Dataset is publicly available at:

https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset

Please download the dataset before running the notebook.

## Code

Run the notebook:

`Crop-Digital-Twin-LDTIA.ipynb`

## Requirements

- Python 3.10+
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib

## Citation

If you use this work, please cite the associated research paper after publication.
