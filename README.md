# 🎗Breast-Cancer-Analysis-using-Machine-Learning-💊🩺🎗🖥
This project uses a Random Forest Classifier to predict breast cancer outcomes and applies SHAP analysis to interpret the model's predictions. It provides insights into the key features influencing the classification of malignant or benign tumors.

## Overview
This project aims to predict the presence of breast cancer in patients using machine learning techniques, specifically the Random Forest Classifier algorithm. The model is trained on a dataset of various features such as tumor characteristics, and its goal is to classify whether the tumor is malignant or benign. Additionally, SHAP (SHapley Additive exPlanations) analysis is employed to explain the model's predictions, providing insights into which features contribute the most to the classification decision.

## Project Features
**Data Preprocessing:** The raw data is cleaned, missing values are handled, and features are scaled for optimal model performance.

**Modeling:** A Random Forest Classifier is used to train the model and predict the likelihood of cancer being malignant or benign.

**SHAP Analysis:** SHAP values are calculated to explain the contributions of different features to the model's predictions, making the model more interpretable.

## Dataset
This project uses the Breast Cancer Wisconsin (Diagnostic) dataset available from the UCI Machine Learning Repository or the sklearn.datasets module. The dataset contains various features related to the characteristics of cell nuclei present in breast cancer biopsies.

## Features include:

**Radius, texture, perimeter, area, smoothness, compactness, concavity, and other tumor properties.**

## Steps Involved
**Data Loading:** Import the dataset into the project and prepare the data for analysis.

**Data Preprocessing:** Clean the data, handle missing values, and perform feature scaling.

**Model Training:** Train a Random Forest Classifier model to predict whether a tumor is malignant or benign.

**Model Evaluation:** Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.

**SHAP Analysis:** Perform SHAP analysis to explain the model's predictions and interpret the contribution of each feature to the classification decision.

## Requirements

Python 3.x
- [pandas](pandas)
- [numpy](numpy)
- [matplotlib](matplotlib)
- [seaborn](seaborn)
- [scikit-learn](scikit-learn)
- [shap](shap)

**You can install the required libraries using the following command:**
```bash
pip install -r requirements.txt
```

## How to Run the Project
**1. Clone the repository:**
```bash
git clone https://github.com/yourusername/breast-cancer-analysis.git
cd `path` breast-cancer-analysis
```
**2. Run the script for training the model and SHAP analysis:**
```bash
python breast_cancer_analysis.py
```

**View the SHAP analysis results:**

The SHAP analysis visualizations will be generated and saved in the output directory.

## Results
The Random Forest Classifier model achieves an accuracy of 96% on the test dataset.

The SHAP analysis shows that features like [feature names] contribute the most to the model’s predictions.

## Conclusion
This project demonstrates how machine learning, specifically Random Forest Classifier, can be used to predict breast cancer diagnoses, with added transparency through SHAP analysis. By analyzing the SHAP values, we can interpret which features are most important for the model's decisions, helping healthcare professionals understand the reasoning behind predictions.
