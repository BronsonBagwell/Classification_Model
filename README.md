# Classification Model
Predicting graduate admission outcomes using logistic regression with manual backward selection to all-significant predictors (GRE, LOR, CGPA).

## Overview
This project builds a logistic regression classification model to predict whether a student will be admitted to a graduate program. The analysis uses manual backward selection to arrive at a model in which all predictors (GRE, LOR, CGPA) are significant, and evaluates predictive performance using ROC curves and confusion matrices.

## Dataset
- **Source:** Graduate Admission dataset (500 records)
- **Key variables:** GRE Score, TOEFL Score, University Rating, SOP, LOR, CGPA, Research Experience, Admission outcome

## Methods
- Binary logistic regression (`glm`, binomial family); manual variable selection; evaluation via confusion matrix, ROC, and AUC (`ROCR`)

## Key Findings
- GRE Score, LOR, and CGPA were the significant predictors of admission retained by backward selection
- The final model clearly outperforms the 77.5% benchmark accuracy on the test set

## Tools & Libraries
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white)
![caret](https://img.shields.io/badge/caret-276DC3?style=flat-square&logo=r&logoColor=white)
![ROCR](https://img.shields.io/badge/ROCR-276DC3?style=flat-square&logo=r&logoColor=white)
![ggplot2](https://img.shields.io/badge/ggplot2-276DC3?style=flat-square&logo=r&logoColor=white)
![dplyr](https://img.shields.io/badge/dplyr-276DC3?style=flat-square&logo=r&logoColor=white)
![tidyverse](https://img.shields.io/badge/tidyverse-1A162D?style=flat-square&logo=r&logoColor=white)

## How to Run
1. Clone the repository: `git clone https://github.com/BronsonBagwell/Classification_Model.git`
2. Open the HTML file in a browser, or run the R Markdown file in RStudio
3. Required packages: `caret`, `ROCR`, `ggplot2`, `dplyr`, `tidyverse`
