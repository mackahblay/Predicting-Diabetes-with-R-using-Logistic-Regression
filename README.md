# Predicting-Diabetes-with-R-using-Logistic-Regression

Author: Melchizedek Ackah-Blay

## Overview

This project focuses on predicting diabetes diagnosis using logistic regression modeling. The dataset, after thorough cleaning and preparation, consists of 403 observations with variables such as age, gender, BMI, and diabetes diagnosis status. Logistic regression is utilized to identify significant predictors of diabetes and quantify their impact on the likelihood of diagnosis. The analysis aims to provide insights into the relationship between demographic and health-related factors and the probability of being diagnosed with diabetes.
Key Tasks and Activities

## Data Cleaning/Preparation:
- Imported the diabetes dataset and converted height and weight variables to SI units for consistency.
- Calculated BMI using the formula and categorized BMI into four groups: underweight, normal, overweight, and obese.
- Recoded insurance and smoking variables into meaningful labels for analysis.
- Conducted checks to ensure the accuracy of the recoded variables and generated summary statistics to understand the dataset's characteristics.

## Exploratory Data Analysis (EDA):
- Analyzed the distribution of characteristics within the dataset, including BMI categories, gender distribution, and diabetes diagnosis status.
- Calculated percentages to understand the prevalence of obesity, gender representation, and diabetes diagnosis within the dataset.
- Visualized the relationship between BMI and cholesterol levels using a scatter plot and explored the age distribution of individuals using a histogram.

## Data Visualization:
- Visualized the frequency distribution of insurance categories and smoking status using bar plots to understand the distribution of these variables within the dataset.
- Created a scatter plot to visualize the relationship between BMI and cholesterol levels, highlighting the trend using a regression line.
- Examined the age distribution of individuals using a histogram to understand the prevalence of different age groups within the dataset.

## Logistic Regression Analysis:
- Built a logistic regression model to predict diabetes diagnosis based on age, gender, and BMI.
- Interpreted the coefficients of the logistic regression model to understand the impact of each predictor on the likelihood of diabetes diagnosis.
- Assessed the significance of predictors and their contribution to the model's predictive power.

## Conclusion

The logistic regression analysis revealed significant predictors of diabetes diagnosis, including age, gender, and BMI. For every one-year increase in age, the log-odds of diabetes diagnosis increased by 0.055454, while a one-unit increase in BMI led to a log-odds increase of 0.073879. Additionally, being male (compared to being female) was associated with a log-odds increase of 0.244852 for diabetes diagnosis. These findings provide valuable insights into the factors influencing diabetes diagnosis and can aid in early detection and prevention efforts. Future research could explore additional predictors of diabetes diagnosis, such as genetic factors and lifestyle variables, to enhance the accuracy of predictive models. Additionally, longitudinal studies could investigate the temporal relationship between predictors and diabetes onset, providing a deeper understanding of disease progression and risk factors.
