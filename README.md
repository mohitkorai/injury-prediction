# Injury Prediction - R Data Science Project

This project focuses on predicting injuries using structured data and machine learning techniques in R. The analysis covers feature exploration, model building, and result interpretation using R Markdown and visualization libraries.

📄 **View the interactive report:** [Injury Prediction HTML Report](https://mohitkorai.github.io/injury-prediction/)  
📈 **Tools Used:** R, ggplot2, caret, randomForest, rmarkdown

---

## 🔍 Problem Statement

The goal is to analyze structured injury-related data and build predictive models that can classify individuals based on their injury status. The project involves data cleaning, feature engineering, exploratory analysis, and applying classification models.

---

## 📂 Project Overview

This R Markdown notebook demonstrates a complete data science pipeline:

- **Data Preprocessing**
  - Loaded and structured injury data
  - Handled missing values and outliers
  - Categorical encoding and normalization

- **Exploratory Data Analysis (EDA)**
  - Visualizations using `ggplot2`
  - Correlation heatmaps and injury trend analysis

- **Modeling**
  - Trained multiple classification models:
    - Logistic Regression
    - Random Forest
    - Naïve Bayes
    - k-Nearest Neighbors (kNN)
  - Evaluated using confusion matrices, sensitivity, specificity, and accuracy

- **Result Interpretation**
  - Compared models based on performance
  - Identified the most reliable model for practical use in EMS

---

## 📊 Results Summary

| Model                  | Accuracy |
|------------------------|----------|
| Random Forest          | 84.02%   |
| Logistic Regression    | 73.82%   |
| Naïve Bayes            | 73.59%   |
| K-Nearest Neighbors    | 72.27%   |

> Random Forest achieved the highest accuracy and best overall performance, making it the most suitable model for injury prediction in emergency response contexts.

---

## 🧰 Tools & Libraries

- **R & R Markdown**
- `ggplot2` (visualization)
- `caret` (model training)
- `randomForest`, `e1071`, `class` (ML models)
- `dplyr`, `tidyr` (data manipulation)

---

## 📁 Repository Contents

- `index.html`: [Interactive HTML Report](https://mohitkorai.github.io/injury-prediction/)
- `Injury_Prediction.Rmd`: Source notebook with full analysis
- `README.md`: Project overview and results

---

## 📌 Author

**Mohit Venkata Rama Swamy Korai**  
Data Science and Machine Learning professional  
[GitHub](https://github.com/mohitkorai) • [Kaggle](https://www.kaggle.com/mohitkorai) • [LinkedIn](https://www.linkedin.com/in/venkatasw/)
