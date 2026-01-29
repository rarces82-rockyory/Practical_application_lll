# Practical_application_lll
# Comparing Classification Models for Bank Marketing Campaigns
https://github.com/rarces82-rockyory/Practical_application_lll.git

## Project Overview
This project evaluates and compares multiple machine learning classification models to predict whether a client will subscribe to a bank term deposit based on marketing campaign data from a Portuguese banking institution.

The models analyzed include:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Machine (SVM)

## Business Objective
The goal is to assist marketing teams in identifying potential subscribers more effectively by comparing model performance and understanding trade-offs between accuracy, recall, and interpretability.

## Data
The dataset was sourced from the UCI Machine Learning Repository and contains over 45,000 records with demographic, financial, and campaign-related features. The target variable indicates whether a client subscribed to a term deposit.

## Methodology
- Data preprocessing and encoding using scikit-learn Pipelines
- Train/test split for model evaluation
- Baseline accuracy calculation
- Model training and comparison using accuracy
- Hyperparameter tuning with GridSearchCV
- Additional evaluation using recall and F1-score to address class imbalance

## Key Findings
- All models achieved test accuracy around 89%, slightly above the baseline.
- Accuracy alone was insufficient due to class imbalance.
- Recall and F1-score revealed limited ability to identify actual subscribers.
- Logistic Regression provided the best balance of performance, efficiency, and interpretability.

## Recommendations
Future improvements should focus on recall-oriented strategies, such as class weighting, resampling techniques, and threshold optimization, to better identify clients likely to subscribe. The use of Marketing benchmark will provide a better outcome

## Repository Structure
- `notebooks/`: Jupyter Notebook containing full analysis
- `README.md`: Project summary and findings

## Author
Roy
