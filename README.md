# wine-dataset-training

Dataset

Dataset used: Wine Quality Dataset

Features include:

Alcohol
pH
Citric Acid
Sulphates
Density
Volatile Acidity
Residual Sugar
Chlorides

Target:

Good Wine (1)
Bad Wine (0)

The quality column was converted into binary classification:

Quality ≥ 7 → Good Wine
Quality < 7 → Bad Wine
Technologies Used
Python
Pandas
Matplotlib
Seaborn
Scikit-learn
Google Colab
Machine Learning Model

Model Used:

Random Forest Classifier

Why Random Forest?

High accuracy
Handles classification problems well
Provides feature importance
Reduces overfitting
Project Workflow
Upload and load dataset
Data preprocessing
Convert wine quality into binary labels
Visualize correlations using heatmap
Split data into training and testing sets
Train Random Forest model
Predict wine quality
Evaluate model accuracy
Visualize feature importance
Outputs

The project generates:

First 5 rows of dataset
Correlation Heatmap
Model Accuracy
Confusion Matrix
Feature Importance Graph
