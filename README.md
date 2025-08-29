# student-performance-analysis
An R-based statistical analysis predicting student GPA and project completion likelihood using linear and logistic regression.
# 📊 Student Performance Analysis

## 📖 Project Overview
This project involves a comprehensive statistical analysis of student data to identify key factors influencing academic performance. The work was completed as part of the CS5801 coursework at Brunel University London. The analysis includes:

- **Data Cleaning & Wrangling:** Handling inconsistencies and preparing data for analysis.
- **Exploratory Data Analysis (EDA):** Uncovering patterns and relationships through visualizations.
- **Predictive Modeling:**
  - **Linear Regression:** To predict continuous `grade_point_average` (GPA).
  - **Logistic Regression:** To model the likelihood of a student `completed.extended.project`.

## 🛠️ Tech Stack & Methodology
- **Language:** R
- **Libraries:** `tidyverse`, `caret`, `car`, `pROC`, `skimr`, `naniar`, `ggplot2`
- **Methods:** Linear Regression, Logistic Regression, Stepwise Selection, Multicollinearity Detection (VIF), Residual Analysis, Data Visualization

## 🔑 Key Insights & Results
- **GPA Prediction (Linear Model):** The final model achieved an **Adjusted R² of 0.628**, identifying `sat_score`, `percentage_absence`, and `commute_method` as significant predictors of a student's GPA.
- **Project Completion (Logistic Model):** The model highlighted challenges in predicting binary outcomes with the available data, providing valuable lessons on model selection and feature importance.
- **EDA Findings:** Established a clear positive correlation between SAT scores and GPA, and identified the distribution of student commute methods.
- ## 📁 Project Structure
student-performance-analysis/
├── analysis/ # R Markdown source file and rendered output
├── data/ # Information on the data source
├── outputs/ # Generated graphs and visualizations
└── README.md
- ## 👨‍💻 Developer
**Nazeeb Ullah**
- MSc Data Science & Analytics | Economist
- [LinkedIn](https://www.linkedin.com/in/nazeeb-ullah-a812a3105)
- [GitHub](https://github.com/nazeebullah)

---
*This project was completed for the CS5801 module at Brunel University London.*
