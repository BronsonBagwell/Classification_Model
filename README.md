# Classification Model
Predicting graduate admission outcomes using Logistic Regression, Decision Tree, and Random Forest classifiers.

## Overview
This project builds and compares multiple classification models to predict whether a student will be admitted to a graduate program. The analysis applies regularization techniques (LASSO and Ridge) to logistic regression alongside tree-based methods to evaluate predictive performance.

## Dataset
- **Source:** Graduate Admission dataset (500 records)
- **Key variables:** GRE Score, TOEFL Score, University Rating, SOP, LOR, CGPA, Research Experience, Admission outcome

## Methods
- Logistic Regression with LASSO (L1) and Ridge (L2) regularization via `glmnet`
- Decision Tree classification
- Random Forest classification
- Model evaluation using confusion matrices and ROC curves via `ROCR`

## Key Findings
- CGPA, GRE Score, and TOEFL Score were the strongest predictors of admission
- Regularization helped reduce overfitting in the logistic regression model
- Random Forest provided robust classification performance across evaluation metrics

## Tools & Libraries
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white)
![caret](https://img.shields.io/badge/caret-276DC3?style=flat-square&logo=r&logoColor=white)
![glmnet](https://img.shields.io/badge/glmnet-276DC3?style=flat-square&logo=r&logoColor=white)
![ROCR](https://img.shields.io/badge/ROCR-276DC3?style=flat-square&logo=r&logoColor=white)
![ggplot2](https://img.shields.io/badge/ggplot2-276DC3?style=flat-square&logo=r&logoColor=white)

## How to Run
1. Clone the repository: `git clone https://github.com/BronsonBagwell/Classification_Model.git`
2. Open the HTML file in a browser, or run the R Markdown file in RStudio
3. Required packages: `caret`, `glmnet`, `ROCR`, `ggplot2`
