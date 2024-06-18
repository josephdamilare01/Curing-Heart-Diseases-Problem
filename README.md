# Project Description: Predicting Heart Disease through Lifestyle Factors
Heart disease remains a significant global health challenge, contributing to substantial morbidity and mortality rates. Understanding and mitigating the factors that lead to heart disease is crucial for improving public health outcomes. This project aims to develop a robust and effective machine learning model to predict heart disease based on key lifestyle factors, specifically biking and smoking habits.

# Project Objective
The primary objective of this project is to create a predictive model that can accurately estimate the likelihood of heart disease in individuals using data on their biking and smoking behaviors. By leveraging statistical analysis and machine learning techniques, we aim to identify the extent to which these lifestyle factors influence heart disease risk, providing valuable insights that can inform public health strategies and individual lifestyle choices.

# Data and Methodology
The dataset used in this project includes three main variables:

- Biking: Amount of biking activity (units not specified).
- Smoking: Smoking habits quantified (units not specified).
- Heart Disease: Measure of heart disease presence (units not specified).
## Summary Statistics
- Biking: The biking activity in the dataset ranges from a minimum of 1.119 to a maximum of 74.907, with a mean of 37.788. This indicates a considerable variation in biking habits among individuals.
- Smoking: Smoking habits range from 0.5259 to 29.9467, with a mean of 15.4350, showing substantial variability in smoking behavior.
- Heart Disease: The heart disease variable ranges from 0.5519 to 20.4535, with a mean of 10.1745, suggesting diverse levels of heart disease prevalence.
## Normality Tests
The Shapiro-Wilk tests for normality indicated that the distributions of biking, smoking, and heart disease do not follow a normal distribution. This finding informed our choice of statistical techniques and model evaluations.

## Correlation Analysis
A strong negative correlation was found between biking and heart disease (correlation coefficient of -0.9355), indicating that increased biking is associated with reduced heart disease.
A moderate positive correlation was found between smoking and heart disease (correlation coefficient of 0.3091), suggesting that higher smoking levels are linked to increased heart disease.
# Linear Regression Model
A linear regression model was developed using biking and smoking as predictors for heart disease. The model demonstrated high explanatory power, with an R-squared value of 0.9796, indicating that approximately 97.96% of the variability in heart disease could be explained by these two predictors. Key findings from the model include:

- Biking: Each additional unit of biking activity reduces the heart disease score by 0.2001 units.
- Smoking: Each additional unit of smoking increases the heart disease score by 0.1783 units.
# Conclusion
This project underscores the significant impact of lifestyle factors, such as biking and smoking, on heart disease risk. The predictive model developed provides strong evidence that increased physical activity (biking) is associated with lower heart disease prevalence, while higher smoking levels correlate with increased heart disease risk. These insights highlight the importance of promoting healthier lifestyle choices to combat heart disease.

Future work could expand the dataset to include additional variables and employ more sophisticated machine learning techniques to further refine the predictive model. Ultimately, this project aims to contribute to the broader effort of reducing heart disease through data-driven insights and targeted interventions.

# NOTE: you can access the code on Kaggle with the link below
[An Effective Way of Curing Heart Diseases Problem](https://www.kaggle.com/code/adekunlejoseph/an-effective-way-of-curing-heart-diseases-problem)

