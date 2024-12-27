# codetech-Task2
NAME : Abhinaba dey
---
COMPANY : CODTECH IT SOLUTIONS
---
ID : CT08DXK
---
DOMAIN : Machine learning
---
DURATION : december 2024 to january 2025
---
MENTOR : Sravani gouni
---

**OVERVIEW OF THE PROJECT** : Implement linear regression to predict housing prices based on features like
square footage, number of bedrooms, and location. Use a dataset like the
Boston Housing dataset for training and evaluation.

1. Problem Definition
The goal is to predict housing prices based on features like:

Square footage (e.g., number of rooms).
Socioeconomic factors (e.g., percentage of lower-status population).
Location-related features.
Linear regression assumes a linear relationship between the target variable (housing price) and the input features.

2. Dataset
Use a dataset like the Boston Housing dataset (or similar).
Features include:
Crime rate, number of rooms, proximity to employment centers, etc.
Target: Median value of owner-occupied homes (in $1000s).
3. Steps to Implement
Step 1: Load Data
Load the dataset into a DataFrame.
Inspect the data structure, check for missing values, and understand feature distributions.
Step 2: Preprocessing
Select relevant features for prediction (e.g., number of rooms, crime rate, etc.).
Scale the features (e.g., using StandardScaler) for consistent input magnitudes.
Split the dataset into training and testing sets.
Step 3: Train Linear Regression Model
Use Linear Regression from scikit-learn.
Fit the model to the training data.
Step 4: Evaluate Model
Use metrics like:
Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.
R² Score: Represents the proportion of variance explained by the model.
Step 5: Interpret Results
Analyze model coefficients to understand the importance of features.
Use residual plots to assess the quality of predictions.
