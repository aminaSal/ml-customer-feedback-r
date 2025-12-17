# Machine Learning – Customer Feedback Analysis (R)

## Project Overview
This project analyzes customer feedback from an online food ordering platform
using supervised and unsupervised machine learning techniques in R.

The objective is to identify the socio-demographic factors influencing
positive and negative customer feedback and to compare model performance.

## Dataset
- Source: Kaggle – Online Food Ordering Dataset
- Observations: 388 customers
- Target variable: Customer Feedback (Positive / Negative)

## Methods
### Supervised Learning
- Logistic Regression
- Decision Tree (rpart)
- Random Forest
- Support Vector Machine (SVM)
- Lasso Regression
- PCA + Logistic Regression

### Unsupervised Learning
- K-means Clustering
- Hierarchical Clustering
- Principal Component Analysis (PCA)

## Key Results
- Random Forest achieved the best performance (Accuracy ≈ 84.5%, high specificity, improved sensitivity).

- Age, Monthly Income and Family Size are the most important predictors.

- Clustering revealed distinct customer segments with different feedback patterns.

## Repository Structure
- notebooks/ → R Markdown analysis

- reports/ → PDF report

- data/` → dataset


## Tools
- R, caret, randomForest, rpart, glmnet, factoextra, ggplot2

