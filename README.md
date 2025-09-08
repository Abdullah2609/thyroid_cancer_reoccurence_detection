# Thyroid Cancer Recurrence Prediction Model

## Overview
A machine learning project that predicts thyroid cancer recurrence using clinical data. The model processes patient records including demographics, tumor characteristics, and treatment history to forecast the likelihood of cancer recurrence.

## Features
- Data preprocessing and feature engineering
- Handling of imbalanced medical data
- XGBoost classification model
- Comprehensive evaluation metrics
- Visualization of results

## Technical Stack
- Python 3.x
- Key Libraries:
  - pandas
  - numpy
  - scikit-learn
  - XGBoost
  - matplotlib
  - seaborn

## Project Structure
```
thyroid_cancer/
├── dataset.csv           # Clinical data (not included)
├── thyroid_cancer.ipynb  # Main notebook with analysis
└── README.md
```

## Model Features
- Patient demographics
- Clinical history
- Tumor characteristics (T, N, M staging)
- Treatment response
- Risk assessment

## Usage
1. Clone the repository
2. Install required packages:
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
```
3. Place your dataset as 'dataset.csv' in the project root
4. Run the Jupyter notebook:
```bash
jupyter notebook thyroid_cancer.ipynb
```

## Model Performance
- Handles class imbalance using `scale_pos_weight`
- Evaluation metrics include:
  - Accuracy
  - Precision
  - Recall
  - F1-score

## Data Requirements
The input dataset should contain the following features:
- Age
- Gender
- Smoking history
- Radiotherapy history
- TNM staging
- Risk assessment
- Treatment response

Author: Abdullah Sakeeb    
