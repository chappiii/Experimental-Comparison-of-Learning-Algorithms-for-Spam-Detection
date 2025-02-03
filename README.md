# Experimental Comparison of Learning Algorithms for Spam Detection

This repository contains a Jupyter Notebook that compares three classification algorithms—**Logistic Regression**, **Random Forest**, and **XGBoost**—for spam detection. The evaluation uses stratified 10-fold cross-validation and assesses each model based on training time, accuracy, and F1 score. Statistical tests (Friedman and Nemenyi) are also performed to determine significant differences among the models.

## Contents

- **Notebook:** `spam_detection_comparison.ipynb`  
  (Contains the complete sequential code execution for data processing, model training, evaluation, and statistical testing.)
  
- **Report:** A detailed report outlining the experimental setup, results, and conclusions.

## Requirements

- Jupyter Notebook

### Python Libraries

Ensure you have the following libraries installed:
- `scikit-learn`
- `xgboost`
- `numpy`
- `pandas`

You can install them using:

```bash
pip install -r requirements.txt
