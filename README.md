# Car-Sales-Project
## Table of Contents
- [Project Overview.](#project-overview)
- [Reasons for making this project.](#reasons-for-making-this-project)
- [Tools Used.](#tools-used)
- [Tasks Performed.](#task-performed)
- [Tableau DashBorad screenshot and link](#tableau-dashBorad-screenshot-and-link)
- [Results and Findings.](#results-and-findings)

## Project Overview:
The Car Sales Project involves loading and cleaning the dataset, handling missing values, and dealing with outliers to prepare for analysis. Exploratory Data Analysis (EDA) is conducted to understand the distribution of key features like mileage, engine size, and year. Feature engineering steps include dropping irrelevant columns and creating dummy variables for categorical data. The project then builds a linear regression model, ensuring that OLS assumptions are met and checking for multicollinearity. After evaluating the model using R-squared metrics, further improvements are made by refining the data, such as removing specific outliers, which ultimately increases the model's accuracy by 14%.

## Reasons for making this project:
- Predictive Modeling: To predict car prices or sales based on various factors like mileage, engine size, and year.
- Data Insights: To gain insights into the key factors that influence car sales or prices.
- Academic or Learning Purpose: To practice data analysis, feature engineering, and regression modeling techniques.
- Outlier Identification: To identify and understand unusual data points that might affect pricing or sales predictions.
- Model Optimization: To experiment with model refinement techniques like removing outliers and checking multicollinearity to achieve higher accuracy.

## Tools Used:
- Jupyter Notebook-->Data Analysis, Data Cleaning and Preprocessing, Exploratory Data Analysis (EDA), Model Building and EvaluationDocumentation
- Tableau--> Data Visualization

## Task Performed:
1) Importing Libraries: 
- The project begins with the necessary library imports, which are likely essential for data manipulation, visualization, and modeling.
2) Loading and Describing Data:
- Loading the data: The dataset related to car sales is loaded.
- Describing the data: The data is then described, likely using statistical summaries to understand its distribution and characteristics.
- Dropping Model: It seems some columns or specific car models are dropped from the analysis.
- Dealing with missing values: Missing data is handled to ensure the dataset is complete for analysis.

3) Exploratory Data Analysis (EDA):
- Exploring Partial Distribution Function (PDF): The project explores the distribution of key variables.
- Dealing with Outliers: Outliers are identified and dealt with to prevent them from skewing the analysis.
 
4) Feature Engineering:
- Mileage, Engine, Year: Specific features like mileage, engine, and year are explored and likely transformed.
- Cleaned Data: After processing, the data is cleaned and ready for modeling.
  
5) Regression Analysis:
- OLS Assumptions: The Ordinary Least Squares (OLS) assumptions are checked to ensure they hold for linear regression.
- Linear Regression: The dataset is prepared for linear regression analysis.
- Multicollinearity: Multicollinearity among features is checked, likely using VIF (Variance Inflation Factor).
- Creating Dummy Variables: Categorical variables are converted into dummy variables for the regression model.
  
6) Model Building:
- Linear Regression Model: A linear regression model is created.
- Scaling Data: The data is scaled to standardize the features.
- Train-Test Split: The data is split into training and testing sets.
- Model Training: The regression model is trained on the training data.
- Checking R-Squared: The model's performance is evaluated using the R-squared metric.
 -Testing: The model is tested on the testing data.
  
7) Model Improvement:
- Removing Outliers: Further refinement by removing specific outliers (e.g., engine values exceeding 8.4).
- OLS on Cleaned Data: Re-evaluation of the OLS assumptions and model on cleaned data.
- Creating Dummies & Regression: Dummy variables are created again, and the linear regression model is re-built.
- Adj. R-Squared: The adjusted R-squared is calculated, and it’s noted that the accuracy increased by 14% after these adjustments.
  
## tl;dr of task performed:
The project involves importing necessary libraries, loading and describing the car sales dataset, and preparing the data by dropping irrelevant columns and handling missing values. Exploratory Data Analysis (EDA) is conducted to explore distributions and manage outliers. Feature engineering refines attributes like mileage and engine. A linear regression model is built, with OLS assumptions checked and multicollinearity addressed. The model is trained, tested, and evaluated with R-squared. After removing outliers and refining the model, the adjusted R-squared accuracy improves by 14%.

## Tableau DashBorad screenshot and link:
![Screenshot 2024-08-20 173233](https://github.com/user-attachments/assets/968c7408-101a-4faa-9a51-1c3f158af590)
- [link for Tableau Public](https://public.tableau.com/app/profile/anuj.prasad7773/viz/Carsalesdashboard_17241498674550/WithClear)



## Results and Findings:
- Successfully built a linear regression model to predict car prices or sales.
- Emphasis on data cleaning, feature engineering, and model evaluation.
- Addressed missing values, outliers, and multicollinearity to improve the model.
- Achieved a 14% increase in adjusted R-squared after refining the data.
- Mileage, engine size, and year were identified as important factors in predicting car prices.
- Demonstrated that careful data preparation and model optimization lead to more accurate and reliable predictions.
- Avg. mileage based on Engine Type and Brand.
- Types of cars brought by customers.
- Count of model of each brand.
- Avg. mileage and price of each brand.
- Avg. price per year.
