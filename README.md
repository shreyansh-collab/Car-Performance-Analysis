## Car-Performance-Analysis

# Overview
This project uses the classic mtcars dataset to explore relationships between various car attributes. The analysis focuses on regression and decision tree modeling to predict car performance, particularly fuel efficiency (mpg).

# Objectives
1. Exploratory Data Analysis (EDA): Analyze relationships between key variables.
2. Regression Modeling: Predict fuel efficiency (mpg) using multiple linear regression.
3. Decision Tree Modeling: Use decision trees to classify cars based on mpg.

# Dataset
The mtcars dataset contains data on 32 car models with the following attributes:
Predictors: cyl, disp, hp, wt, qsec, etc.
Target Variable: mpg (miles per gallon).

# Steps and Methods
1. Exploratory Data Analysis
Visualized the relationships between variables.
Assessed correlations to identify significant predictors.
2. Regression Modeling
Built a multiple linear regression model to predict mpg.
Evaluated the model using metrics like R-squared and residual analysis.
3. Decision Tree Modeling
Created a decision tree to classify cars based on their fuel efficiency.
Visualized the decision tree for interpretability.
4. Model Evaluation
Compared the performance of regression and classification models.
Assessed model accuracy and interpretability.

# Results
1. Regression Model:
Significant predictors of mpg include wt, hp, and cyl.
Achieved an R-squared value of XX%.
2. Decision Tree Model:
The decision tree identified clear rules for classifying cars by fuel efficiency.

# Key Python Libraries
pandas and numpy for data manipulation.
matplotlib and seaborn for visualization.
scikit-learn for regression and decision tree modeling.

# Visualizations
Scatter Plots:
Visualized relationships between mpg and predictors like wt and hp.
Decision Tree:
Displayed splits based on car attributes, offering clear interpretability.

# How to Run
Clone this repository.
Open the Jupyter Notebook mtcars.ipynb.
Run the code in a Python environment with the required libraries installed.
