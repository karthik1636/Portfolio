
# Suicide Rates Analysis 🎭

## Project Overview 📘
This project conducts a multivariate statistical analysis on global suicide rates to identify patterns, assess the impact of economic factors, and explore the relationships between suicide rates, generation, and economic conditions. The project applies both parametric and non-parametric statistical techniques to assess these relationships. 🎯📊🔍

## Title 🏷️
**Suicide Rates: A Multivariate Analysis of Economic and Demographic Factors**

## Objective 🎯
The goal of this project is to:
- Identify trends in global suicide rates across different demographics and economic conditions.
- Assess the impact of economic downturns on suicide rates.
- Explore generational differences in suicide rates.
- Determine if statistical transformations can normalize the data for improved predictive modeling. 📊🔢🔬

## Data Description 📊
- **Size:** The dataset consists of multiple years of global suicide data, including demographic and economic variables.
- **Sources:** The dataset is compiled from multiple sources, including World Bank economic indicators and suicide statistics from various national databases.
- **Key Variables:**
  - Suicide Count
  - GDP Per Capita
  - Inflation Rate
  - Employment Population Ratio
  - Age Group
  - Sex
  - Country Name
  - Year 📜

## Methodology 🔍🧐📉
### Data Processing:
- Data cleaning and transformation, including handling missing values.
- Data type conversions and standardization.
- Statistical transformation (e.g., Box-Cox transformation) to normalize data where applicable. 📑📌🛠️

### Statistical Analysis:
- **Multivariate Analysis:** Conducted MANOVA to test if groups have different mean vectors for continuous variables.
- **Non-Parametric Tests:** Applied Kruskal-Wallis tests for differences across groups due to non-normality.
- **Time Series Analysis:**
  - Computed Moving Averages and Exponentially Weighted Moving Averages (EWMA) to analyze trends.
  - Conducted seasonal decomposition of suicide rates for different countries.
- **ANOVA and Regression Modeling:**
  - Evaluated generational differences in suicide rates using ANOVA.
  - Built regression models to assess the influence of economic factors.
  - Interaction analysis between generation and economic conditions.
- **Statistical Assumptions Testing:**
  - Assessed normality using Henze-Zirkler and Anderson-Darling tests.
  - Conducted Box’s M test to check homogeneity of covariance matrices.
  - Tested for Simpson’s Paradox in various economic and demographic variables. 📊🔍📉

## Accuracy: ✅📊📏
- **Multivariate Normality:** Data was not multivariate normal, leading to the use of non-parametric methods.
- **Model Performance:**
  - Adjusted R-squared for the generational regression model: **0.85**
  - Adjusted R-squared for the economic impact model: **0.61**
  - MAPE for time series forecasting:
    - Moving Average: **Low error percentage**
    - EWMA: **Low error percentage** 📊📌📏

## Quantifiable Results 📉📌📈
- Significant differences found in suicide rates across **sex, age groups, and countries**.
- **GDP Per Capita** had a significant positive correlation with suicide rates.
- **Employment Population Ratio** showed a significant association with suicide rates.
- **Recession periods** were linked with higher suicide rates across specific generations.
- **Generation X had the highest suicide rate**, while Generation Alpha had the lowest.
- **Box-Cox transformation failed** to normalize the suicide count data. 📊📉🧐

## Project Impact 🌍📢🌱
- **Public Health Insights:** Identifies key economic and demographic risk factors for suicide.
- **Policy Recommendations:** Provides statistical evidence to support targeted mental health interventions.
- **Economic Policy Influence:** Highlights the effect of economic downturns on mental health outcomes.
- **Predictive Modeling Basis:** Establishes a framework for forecasting suicide rates based on economic indicators. 🌍📊🔬

## Tools and Technologies Used 🛠️⚙️💻
- **Programming Language:** R
- **Libraries Used:**
  - Data Processing: `tidyverse`, `dplyr`, `readr`
  - Visualization: `ggplot2`, `gridExtra`
  - Statistical Analysis: `car`, `MVN`, `biotools`, `nortest`, `rstatix`, `ICSNP`
  - Time Series Analysis: `zoo`, `stats` 🛠️📈💡

---

### Contributors 👨‍💻👥📜
- **Author:** Karthik Mettu
- **Contact:** [GitHub Profile](https://github.com/karthik1636)  🎯📌📬

