# Customer Spending Prediction

## Abstract
This project, authored by Aryan Mainkar, integrates customer demographic data and sales transactions using a Random Forest Regressor to predict individual spending behavior. The study explores the impact of age, gender, and payment methods, aiming to refine marketing strategies based on a granular understanding of customer characteristics.

## Introduction
Understanding and predicting customer behavior is essential for businesses striving to optimize marketing strategies and enhance customer engagement. This study employs machine learning techniques to predict individual customer spending patterns, with the primary objective of developing a predictive model for tailoring marketing strategies to individual customer profiles.

## Problem Statement
Effectively predicting customer spending is crucial for businesses seeking to optimize marketing efforts. This study addresses this challenge by merging and preprocessing datasets, employing a sophisticated Random Forest Regressor to unravel the complexities of spending patterns.

## Proposed Methodology

### 1. Data Exploration
   - **Loading and Initial Exploration:** Two datasets on customer demographics and sales transactions are loaded.
   - **Exploratory Data Analysis (EDA):** Uncovering insights into age distribution, gender representation, payment methods, and sales distribution.

### 2. Data Preprocessing
   - **Merging Datasets:** Integration of customer and sales datasets based on customer ID.
   - **Feature Engineering:** Introduction of a new feature, total spending per customer.

### 3. Modelling
   - **Random Forest Regression:** Employing a powerful Random Forest Regressor to predict total spending accurately.
   - **Model Evaluation:** Utilizing quantitative metrics, including Mean Squared Error (MSE) and R-squared, to assess model performance.

## Analysis and Results
The Random Forest Regressor demonstrates exceptional performance, accurately predicting total spending. The analysis reveals the significance of gender and age, providing actionable insights for businesses.

## Conclusions
The study underscores the efficacy of the Random Forest Regressor in accurately predicting customer spending. The research translates these insights into actionable recommendations for businesses, emphasizing the importance of tailoring marketing strategies to specific customer segments.

## Lessons Learned
1. **Data Quality Impact:** Meticulous data preprocessing significantly influences predictive model robustness.
2. **Feature Importance Insights:** Age and gender emerge as critical factors influencing customer spending.
3. **Visualization Enhancement:** Advanced visualization techniques, such as 3D plots, facilitate a deeper understanding of model complexities.
4. **Model Evaluation Metrics:** Comprehensive model evaluation metrics provide a thorough assessment of accuracy and explanatory power.

## Bibliography
- Breiman, L. (2001). Random forests. Machine learning, 45(1), 5-32.
- Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., ... & Duchesnay, É. (2011). Scikit-learn: Machine learning in Python.
- McKinney, W. (2010). Data structures for statistical computing in Python.
- Seabold, S., & Perktold, J. (2010). Statsmodels: Econometric and statistical modeling with python.
