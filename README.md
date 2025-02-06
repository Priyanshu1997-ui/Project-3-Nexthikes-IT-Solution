# House Price Prediction using Machine Learning

# Overview:-
This project aims to predict house prices based on various features like location, size, amenities, and quality. We used exploratory data analysis (EDA), feature engineering, and multiple machine learning models to find the best predictive model.

# Dataset:-
The dataset includes various features of houses, such as:
1.Lot Area, Year Built, Neighborhood
2.Number of Rooms, Bathrooms, Garage Size
3.Quality and Condition Ratings 
4.Various Porch & Basement Features 

# Project Workflow:-
# 1 .Data Preprocessing & Cleaning
Handled missing values using mean/median imputation and categorical encoding.
Removed outliers using IQR (Interquartile Range) & Winsorization.
Converted categorical variables using Label Encoding & One-Hot Encoding.
# 2.Exploratory Data Analysis (EDA) 
We performed univariate, bivariate, and multivariate analysis using:
Boxplots to detect outliers.
Pairplots & Scatter plots to analyze feature relationships.
Correlation heatmaps to identify highly correlated variables.
# 3.Feature Engineering & Selection 
Created new features such as:
Total_SF (Total Square Footage)
Total_Bathrooms (Sum of all bathrooms)
Quality_Index (Overall Quality & Condition)
Removed redundant or less important features.
# 4.Model Selection & Training 
We trained multiple machine learning models:
Linear Regression
Decision Tree
Random Forest

# Conclusion: 
Random Forest outperformed other models with the lowest error rates.

# Results & Insights
Houses with better quality, larger size, and additional amenities have higher prices.
Features like "Overall Quality" & "Total SF" had the highest impact on house prices.
Removing outliers & irrelevant features significantly improved model performance.
