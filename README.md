# heart-disease-classification
Project Overview

• Machine learning project to classify heart disease presence based on clinical health indicators
• Includes exploratory data analysis, visualization, and predictive modeling
• Helps understand risk factors and medical feature contributions

Objectives

• Analyze patient health features
• Identify patterns associated with heart disease
• Build machine learning models for classification
• Evaluate model accuracy, precision, recall, and confusion matrix
• Identify the most influential predictors

Tools Used

• Python
• Pandas
• NumPy
• Matplotlib
• Seaborn
• Scikit-learn
• Jupyter Notebook

Files in This Repository

• heart_disease_classification.ipynb — Main notebook
• sample_heart_disease.csv — Sample dataset
• README.md — Documentation

Dataset Source

• Original dataset loaded from local storage
• A sample dataset is provided for reference

Important Note (Path Adjustment Required)

• The notebook loads the dataset using a local path
• Users must update this path on their machine
• Alternatively, users may use the included sample_heart_disease.csv

Key Insights

• Certain medical features strongly correlate with heart disease risk
• Age, resting blood pressure, cholesterol, and chest pain type show clear patterns
• Visualizations reveal distinct distributions across target classes
• Correlation heatmaps highlight important clinical relationships

Modeling Summary

• Models tested typically include Logistic Regression, Decision Tree, Random Forest, etc.
• Strong predictive performance achieved after preprocessing
• Feature importance identifies top predictive health indicators
• Confusion matrix results show reliable classification

Medical Interpretation

• Identifies high-risk patient groups
• Helps understand which clinical metrics contribute most to disease prediction
• Useful for early screening and decision support (not for diagnosis)

How to Run

• Download this repository
• Place the sample dataset in the same folder
• Open the notebook in Jupyter
• Update dataset path if needed
• Run all cells sequentially
