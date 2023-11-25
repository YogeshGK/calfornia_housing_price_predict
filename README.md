![plot](./result/cal_housing.jpeg)

# California Housing Price Prediction

This Python project aims to analyze California housing data and predict housing prices using linear regression as the machine learning technique. The project utilizes the popular scikit-learn library for implementing linear regression and handling the machine learning aspects of the analysis.




## Features

    - Data Analysis: The project performs exploratory data analysis on the California housing dataset to understand the patterns and relationships in the data.

    - Linear Regression: Linear regression is employed to build a predictive model for housing prices based on various features present in the dataset.

    - Scikit-learn Library: The project leverages the scikit-learn library to implement the linear regression model, handle data preprocessing, and evaluate the model's performance.


## File Structure


    - ca_housing.ipynb: Jupyter Notebook containing the code for data analysis, model training, and predictions.

    - result/: Directory containing the scatter plots of individual features vs housing price

    - README.md: Project documentation providing an overview, usage instructions, and other relevant information.
# California Housing Price Prediction

This Python project aims to analyze California housing data and predict housing prices using linear regression as the machine learning technique. The project utilizes the popular scikit-learn library for implementing linear regression and handling the machine learning aspects of the analysis.




## Dataset Description
--------------------------

**Data Set Characteristics:**

    :Number of Instances: 20640

    :Number of Attributes: 8 numeric, predictive attributes and the target

    :Attribute Information:
        - MedInc        median income in block group
        - HouseAge      median house age in block group
        - AveRooms      average number of rooms per household
        - AveBedrms     average number of bedrooms per household
        - Population    block group population
        - AveOccup      average number of household members
        - Latitude      block group latitude
        - Longitude     block group longitude

    :Missing Attribute Values: None

This dataset was obtained from the StatLib repository.
https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html

The target variable is the median house value for California districts,
expressed in hundreds of thousands of dollars ($100,000).
## Lessons Learned

### Linear Regression

        1. Its statistical method through which we can model the relationship between a dependent variable and one or more independent variables by fitting a linear equation to the observed data. 
        
        2. Linear equation : Y = a + bX
          Y : dependent variable : Housing price in this project : plotted along Y axis
          X : independent variable : any of feature available in the dataset : plotted along X axis
          b : slope of line 
          a : intercept (value of y when x = 0) 

        3. The goal is to find the best-fitting line (or hyperplane in higher dimensions) that minimizes the sum of the squared differences between the observed and predicted values.
    

### Model Evalaution based on R2 score and Mean squared error (MSE)
        MSE :
            1. The squared term in MSE penalizes large errors more than small errors.
            2. This means that the model is more sensitive to outliers or large deviations 
            from the true values.
            3. By squaring the errors, the MSE gives more weight to larger errors, making it suitable when large errors are considered more critical or when you want the model to pay more attention to extreme values.

        R2 Score :
            1.  It's used to evaluate the goodness of fit of the model to the data.
            2. Also known as coefficient of determination. ranges from 0 to 1
            3. A higher R2 score indicates a better fit of the linear regression model to the test  data. 
            4. It can be interpreted as the proportion of the variance in the dependent variable (y) that is captured by the linear model.


​




