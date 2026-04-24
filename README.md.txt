# Breast Cancer Survival Analysis

This repository contains a machine learning-based survival analysis project for predicting breast cancer patient outcomes using the built-in GBSG2 dataset from `scikit-survival`.

## Project Overview
The project applies survival analysis techniques to clinical breast cancer data and compares two models:
- Cox Proportional Hazards Model
- Random Survival Forest

## Workflow
- Load GBSG2 dataset from `sksurv.datasets`
- Perform exploratory data analysis
- Plot Kaplan–Meier survival curve
- Encode categorical variables using `OrdinalEncoder`
- Split data into training and testing sets
- Train Cox PH and Random Survival Forest models
- Evaluate models using Concordance Index (C-index)
- Visualize predicted survival probability curves

## Results
- Cox PH C-index: 0.6493
- Random Survival Forest C-index: 0.6624

## Dataset
This project uses the built-in GBSG2 breast cancer survival dataset available in the `scikit-survival` library, so no separate dataset file is included in this repository.

## Requirements
Install dependencies using:

```bash
pip install -r requirements.txt
```

## Run
Open the Jupyter notebook and run all cells.

