# Diabetes Prediction using Machine Learning

## Project Overview 📘🔬📊
This project focuses on predicting diabetes risk using machine learning techniques, primarily logistic regression, to analyze key factors influencing diabetes occurrence. The goal is to identify significant predictors, evaluate model accuracy, and develop insights for early intervention and prevention strategies.

## Title 🏷️📑📌
**Diabetes Prediction: Identifying Key Risk Factors and Improving Early Detection**

## Objective 🎯📈🩺
- Develop predictive models to estimate an individual’s risk of developing diabetes.
- Determine and quantify the key factors contributing to diabetes.
- Evaluate different logistic regression models to assess performance.
- Educate individuals on preventive measures to reduce diabetes risk.

## Data Description 📊📦🔍
- **Size:** The dataset consists of **60,000 records**, covering various demographic and medical attributes.
- **Sources:** Data was obtained from **Kaggle**, featuring real-world health metrics.
- **Key Variables:**
  - Age
  - Gender
  - BMI (Body Mass Index)
  - Hypertension
  - Heart Disease
  - Smoking History
  - HbA1c Level
  - Blood Glucose Level
  - Diabetes Diagnosis (0 or 1) 🏥📜📊

## Methodology 🔍📉🛠️
### Data Processing:
- Data cleaning involved handling missing values, correcting categorical inconsistencies, and normalizing numerical variables.
- **One-hot encoding** was applied to categorical variables like gender and smoking history.
- **Oversampling using ROSE** (Random OverSampling Examples) was applied to handle class imbalance.

### Statistical Analysis & Model Building:
- **Exploratory Data Analysis (EDA):**
  - Visualized distributions of key variables such as age, BMI, and glucose levels.
  - Identified significant trends among diabetes-positive and diabetes-negative individuals.
- **Correlation Analysis:**
  - Evaluated relationships between BMI, glucose levels, and diabetes occurrence.
- **Machine Learning Models:**
  - Simple Logistic Regression
  - Reduced Logistic Regression (excluding non-significant variables)
  - Polynomial Logistic Regression (higher-degree terms for improved accuracy)
- **Model Validation:**
  - ANOVA and Chi-squared tests to determine the significance of variables.
  - 10-Fold Cross-Validation and Test Set Evaluation to ensure model reliability.
  - Performance metrics include **F1-score, Accuracy, and ROC-AUC**. 📊🔍📈

## Accuracy & Model Performance ✅📊🔢
- **Multivariate Normality:** The dataset did not follow a strict normal distribution, requiring non-parametric adjustments.
- **Final Model Performance:**
  - Simple Logistic Regression (Oversampled Data) performed best.
  - **F1-score:** 0.85
  - **AUC-ROC:** 0.92
  - **Accuracy:** 87%
- **Key Findings:**
  - **Hypertension** increases diabetes risk by **122%**.
  - **Heart Disease** raises diabetes likelihood by **95%**.
  - **Being Male** increases risk by **42%**.
  - **Smoking** elevates risk, but quitting significantly reduces odds. 📊📉🔬

## Quantifiable Results 📉📈📌
- The best model achieved an **87% accuracy** in predicting diabetes.
- **Hypertension and heart disease** were the strongest predictors.
- **Age & BMI** showed a linear increase in diabetes risk.
- **Oversampling (ROSE)** improved the sensitivity of the model, ensuring better minority class predictions.

## Project Impact 🌍🏥📢
- **Public Health Awareness:** The project emphasizes the importance of lifestyle choices in preventing diabetes.
- **Predictive Analytics:** The findings can be integrated into early screening tools for identifying at-risk individuals.
- **Data-Driven Decision Making:** Insights can guide policy-making and healthcare interventions.
- **Prevention Strategies:** Encourages regular screening, healthy eating, physical activity, and smoking cessation.

## Tools and Technologies Used 🛠️📊💻
- **Programming Language:** R
- **Libraries Used:**
  - Data Processing: `tidyverse`, `dplyr`, `readr`
  - Visualization: `ggplot2`, `ggcorrplot`
  - Statistical Modeling: `MASS`, `glm`, `ROSE`, `car`
  - Validation & Testing: `caret`, `pROC`

---

### Contributors 👨‍💻👥📜
- **Team Members:** Karthik Mettu, Mahamadou Brehima, Swajan Reddy, Jacob Smith.
- **Contact:** [GitHub Profile](https://github.com/karthik1636) 📌📧📜

---
