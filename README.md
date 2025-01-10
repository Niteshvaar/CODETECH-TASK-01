NAME : NITESHVAAR K K
COMPANY : CODTECH IT SOLUTIONS
ID : CT12DS2873
DOMAIN : MACHINE LEARNING
DURATION : DECEMBER 2024 TO FEBRUARY 2025

OVERVIEW OF THE PROJECT

TITLE : 1.	Implementation of  linear regression to predict housing prices based on features like square footage, number of bedrooms, and location.

Objective:

The objective of this project is to build a machine learning model using linear regression to predict housing prices based on features such as square footage, number of bedrooms, and location. The model will be trained and evaluated on a synthetic dataset, and its performance will be assessed using key metrics like Mean Squared Error (MSE) and R-squared (R²).

Key Steps in the Project:

1.Data Generation:
Since no real housing dataset is provided, a synthetic dataset is generated to mimic real-world housing data.
The dataset consists of the following features:
     i.SquareFootage: Size of the house in square feet, modeled as a normal distribution with a mean of 1500 and a standard deviation of 500.
    ii.Bedrooms: The number of bedrooms in the house, randomly chosen between 1 and 5.
   iii.Location: A categorical feature representing the location of the house (encoded as integers 1, 2, or 3).
    iv.Price: The target variable (house price), generated as a linear combination of the features, with added noise to simulate real-world unpredictability.

2.Data Preprocessing:
The synthetic dataset is divided into features (X) and target (y) variables.
The dataset is split into training and testing sets (80% for training, 20% for testing) using train_test_split.

3.Model Training:
A linear regression model from scikit-learn is instantiated and trained on the training data (X_train, y_train).
Linear regression is a method that models the relationship between the dependent variable (house price) and independent variables (square footage, number of bedrooms, location) as a linear equation.

4.Model Evaluation:
Predictions are made on the test set (y_pred).
The model's performance is assessed using two common metrics:
Mean Squared Error (MSE): Measures the average squared difference between the actual and predicted prices. A lower MSE indicates better performance.
R-squared (R²): Represents the proportion of variance in the target variable (house price) that is explained by the model. An R² value closer to 1 indicates a better fit.

5.Visualization:
A scatter plot of actual vs predicted prices is generated. This helps visually assess how well the model is performing. The red dashed line in the plot represents a perfect prediction (where the predicted value matches the actual value).

6.Model Coefficients:
The coefficients of the linear regression model are extracted and displayed. These coefficients indicate the impact of each feature on the house price:
SquareFootage: A higher coefficient means the price increases with more square footage.
Bedrooms: A higher coefficient means the price increases with more bedrooms.
Location: A higher coefficient indicates that certain locations significantly impact the price.

Conclusion:

This project demonstrates how to apply linear regression for predicting housing prices based on features such as square footage, number of bedrooms, and location. The model provides a foundational understanding of how multiple factors influence house prices, while the visualizations and performance metrics offer a clear assessment of the model’s predictive accuracy.


OUTPUT
![image](https://github.com/user-attachments/assets/91a242fa-e704-4bbe-bf47-6ecb01947275)
![image](https://github.com/user-attachments/assets/1937924a-585a-405f-949b-bf71f8c6eb82)
![image](https://github.com/user-attachments/assets/44c99d52-58a2-4264-b34b-2c022040bb11)


