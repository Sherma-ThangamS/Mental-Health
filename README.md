# Mental Health Prevalence Analysis

## Overview
This project aims to analyze and predict mental health prevalence rates across different countries and years. Two datasets, `prevalence-by-mental-and-substance-use-disorder_AI.csv` and `mental-and-substance-use-as-share-of-disease-AI.csv`, were utilized for this analysis. The project involves data cleaning, exploratory data analysis (EDA), data visualization, and machine learning model building.

## Dataset
- Two datasets (`df1` and `df2`) were loaded and merged based on common keys ('Entity' or 'Country' and 'Year').
- The merged dataset (`data`) contains information on various mental health disorders, prevalence rates, and disability-adjusted life years (DALYs) for different countries over multiple years.

## Data Preprocessing
- Irrelevant columns were dropped, and column names were renamed for better readability.
- Label encoding was applied to convert categorical variables ('Country') into numerical format for machine learning model compatibility.

## Exploratory Data Analysis (EDA)
- A correlation heatmap was created using Seaborn to visualize relationships between different mental health indicators.
- A pair plot was generated to observe the pairwise relationships between variables.

## Data Visualization
- A pie chart was created using Plotly Express to show the distribution of mental fitness across different years.
- Line plots were generated to visualize the trend of mental fitness over the years for different countries.

## Machine Learning Model Building
- The project includes the implementation and evaluation of three machine learning models: Linear Regression, Random Forest Regressor, and Support Vector Regression (SVR).
- The models were trained using the available data to predict mental fitness.
- Model performance metrics, including Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared, were used to assess the models.

## Conclusion
- The Random Forest Regressor exhibited outstanding performance, demonstrating low MSE, RMSE, and high R-squared values.
- The project provides insights into mental health prevalence trends and lays the foundation for potential future extensions, such as advanced model exploration and interpretability analysis.

## Future Steps
- Consider more advanced machine learning models and hyperparameter tuning for improved predictions.
- Explore interpretability of the models and conduct feature importance analysis.
- Consider a larger dataset or additional features for a more comprehensive analysis.
