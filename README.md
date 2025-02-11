# American Express - Default Prediction

## Overview
This repository contains notebooks and presentations related to the **American Express - Default Prediction** Kaggle competition. The goal is to build a machine learning model to predict whether a customer will default.

## Repository Structure

### Notebooks:
- **Exploratory Data Analysis (EDA)**: `default-prediction-EDA_MAHFOUDI.ipynb`
- **Feature Engineering**: `default-prediction-feature-engineering_MAHFOUDI.ipynb`
- **Model Training**: `default-prediction-model-training_MAHFOUDI.ipynb`

### Presentations:
- **PDF Version**: `Presentation_ML_Default_MAHFOUDI.pdf`
- **PowerPoint Version**: `Presentation_ML_Default_MAHFOUDI.pptx`

## Model Evaluation
The competition uses a custom metric:
\[
M = 0.5 \times (G + D)
\]
where:
- **G**: Normalized Gini Coefficient
- **D**: Default rate captured at 4%

## Submission Format
```
customer_ID,prediction
00000469ba...,0.01
00001bf2e7...,0.22
0000210045...,0.98
```

## How to Use
1. Explore the **EDA notebook** for data insights.
2. Use the **Feature Engineering notebook** to preprocess data.
3. Train models with the **Model Training notebook**.
4. Review the presentations for insights and project explanations.

## References
- [Competition Page](https://kaggle.com/competitions/amex-default-prediction)
