# Policyholder-Cross-Sell-Prediction-Project

Introduction

The purpose of this project is to leverage machine learning techniques to predict the probability of customers purchasing vehicle insurance based on historical data provided by a large International Insurance company. The dataset contains information about the attempts made by the company to cross-sell car insurance to its current medical insurance policyholders. The objective is to build models that can accurately classify customers into two categories: those who purchased the insurance and those who did not.

Objective

The primary goal of this project is to predict the probability of a customer purchasing car insurance within 30 days post-contact. This prediction is vital for the sales representatives of the company to optimize their efforts and tailor their strategies towards potential customers who are more likely to make a purchase. The project aims to apply various machine learning models to achieve the highest possible predictive accuracy, measured by the AUC ROC (Area Under the Curve) and F-1 score.

About the Dataset

The dataset provided by the insurance company includes several features such as customer demographics (age, gender), policy information (tenure, region), driving-related details (driver's license status, existing car insurance), vehicle characteristics (age, accident history, premium quote), and details about the sales representative involved in the interaction. The target variable, "buy," indicates whether the customer purchased the car insurance (1) or not (0).

Project Flow

The project will follow a structured flow, beginning with the data preparation phase. This involves importing the dataset, performing a train-test split, and evaluating the validity of the split. The subsequent step is the Exploratory Data Analysis (EDA), where descriptive summaries, data manipulations, and visualizations will be conducted to gain insights into the dataset. While analyzing missing values is not mandatory, it is essential to explore potential outliers and erroneous values.

The third section of the project will focus on model development and evaluation. Multiple machine learning algorithms will be considered and trained on the dataset. The model evaluation criteria include AUC ROC and F-1 score. The selected model will then be used to predict the probability of purchase for customers in the Score dataset, and the results will be exported as a .CSV file.
