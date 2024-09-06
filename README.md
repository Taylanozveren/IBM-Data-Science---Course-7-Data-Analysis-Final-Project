# IBM-Data-Science---Course-7-Data-Analysis-Final-Project
House Sales in King County, USA, I will complete the required project in this notebook in a detailed way to make it educational and usable as a review notebook later on.

What steps and methods does the project include?

1. Import Data
The dataset is loaded using the Pandas library. The data includes features such as square footage, the number of bedrooms, number of floors, and price.

2. Data Wrangling
In this phase, the data is cleaned and processed. This includes handling missing values, converting data types, and preparing the data for analysis.

3. Exploratory Data Analysis (EDA)
Key relationships between features and the target variable (price) are explored. This includes using correlation matrices and plotting scatter plots to identify which features are most strongly associated with price. Some strong features identified include:

sqft_living
sqft_above
grade
4. Model Development
Several models are developed to predict housing prices:

Linear Regression is used as a baseline model to predict prices based on square footage and other features.
Polynomial Regression is applied to capture non-linear relationships between features and price.
Ridge Regression is introduced to regularize the model and prevent overfitting, ensuring that the model generalizes well to unseen data.
A pipeline is created to streamline the process of transforming data (e.g., polynomial features) and fitting the regression model.

5. Model Evaluation
The performance of the models is evaluated using metrics such as:

R² (Coefficient of Determination): Measures how well the model explains the variance in the test data.
Mean Squared Error (MSE): Assesses the average squared difference between actual and predicted values.
6. Conclusion
By combining polynomial features with regularization through Ridge regression, the project seeks to balance model complexity and performance. The overall goal is to provide a more accurate and generalized model for predicting housing prices.

This structured approach provides a comprehensive analysis of housing prices based on key features, allowing for informed decisions in real estate investments. ​
