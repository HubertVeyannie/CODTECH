***Overview***

The project uses a dataset containing attributes like the number of rooms, crime rate, property tax rate, and more to predict the median housing price in $1000s. This is a classic regression problem and is ideal for learning supervised machine learning concepts.

***Steps to run the project***

**1. Prerequisites**
Ensure the following are installed:

Python 3.8 or above
Required libraries:
*pip install pandas numpy matplotlib scikit-learn*
**2. Setup**
Download the project files, including the Python script and the BostonHousing.csv dataset.
Place the dataset in the same directory as the script.
**3. Execute the Script**
Run the script in your terminal:

*python linear_regression_housing.py*

***Project Workflow***
**Dataset Loading:** The dataset is loaded and explored to understand its structure and features.
**Data Preprocessing:** The dataset is prepared for training by separating features and target variables.
**Train-Test Split:** The data is divided into training and testing sets to evaluate model performance.
**Model Training:** A Linear Regression model is trained on the training data.
**Model Evaluation:** Performance is measured using metrics like Mean Squared Error (MSE).
**Visualization:** A scatter plot compares actual vs. predicted prices to assess the model's accuracy.

**Information about the dataset**

Downloaded from kaggle

There are 14 attributes in each case of the dataset. 
They are:
CRIM - per capita crime rate by town
ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS - proportion of non-retail business acres per town.
CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX - nitric oxides concentration (parts per 10 million)
RM - average number of rooms per dwelling
AGE - proportion of owner-occupied units built prior to 1940
DIS - weighted distances to five Boston employment centres
RAD - index of accessibility to radial highways
TAX - full-value property-tax rate per $10,000
PTRATIO - pupil-teacher ratio by town
B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT - % lower status of the population
MEDV - Median value of owner-occupied homes in $1000's

