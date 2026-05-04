E-commerce Customer Purchase Prediction

Project Overview This project focuses on predicting whether a customer will make a purchase based on their browsing behavior and product interaction data using supervised machine learning techniques. The analysis is performed using an E-commerce dataset and includes multiple research questions (RQ1–RQ7) covering model performance, preprocessing, feature importance, and business insights.

Dataset Name: Marketing and Product Performance Dataset

Source:https://www.kaggle.com/datasets/carrie1/ecommerce-data 

Description: The dataset contains customer behavior data such as pages viewed, session duration,discounts, cart value, and demographic features.


#Objective To build machine learning models that can accurately predict whether a customer will purchase a product.


Target Variable

Purchased

Yes → 1

No → 0

Type of Problem - Binary Classification

Machine Learning Models Used

Logistic Regression

Decision Tree

K-Nearest Neighbors (KNN)

Random Forest

Evaluation Metrics The models are evaluated using:

->Accuracy

->Precision

->Recall

->F1-score

->AUC (Area Under ROC Curve)

->Confusion Matrix

Research Questions

RQ1: Baseline model performance

RQ2: Model comparison

RQ3: Effect of preprocessing

RQ4: Feature importance analysis

RQ5: Hyperparameter tuning

RQ6: Model robustness

RQ7: Business insights
 
#How to Run the Project

Download the dataset from Kaggle(sometimes dataset will be unavailable) Or I have uploaded My dataset Previously in Teams

Place the dataset file in your working directory

Open Jupyter Notebook

Run notebooks in order:

RQ1 → RQ7

Outputs will be generated as:

CSV tables
PDF figures

Results Summary

Random Forest achieved the best performance across most metrics
Preprocessing (scaling) improved model accuracy

Feature importance analysis shows that:

Pages viewed

Session duration

Discounts are key predictors of purchase behavior

Observations

Some models (e.g., Decision Tree and Random Forest) achieved very high accuracy, which may indicate overfitting. Further validation techniques can be applied to improve generalization.

Outputs

Tables: Saved as .csv files

Figures: Saved as .pdf files

Requirements

Install dependencies

Libraries Used
pandas
numpy
matplotlib
seaborn
scikit-learn

Note
The repository is public and contains all required files for evaluation.
All notebooks are executed with visible outputs.
