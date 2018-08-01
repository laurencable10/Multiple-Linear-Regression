# Multiple Linear Regression
## Using Sacramento Real Estate Data
* This notebook continues to hone EDA skills using the Pandas library while practicing constructing simple linear regressions using both Stats Models Scikit-Learn in order to predict housing prices.
* The dataset utilized contains information on qualities of property, location of property, and time of sale in Sacramento, California in May of 2008

## Overview 

### Exploratory Data Analysis 
- Leveraging the .describe( ) method to produce notable findings and do necessary data clean-up
- Engineering new features using the .get_dummies( ) that eoncodes attributes with two or more distinct categories/levels as binary variables.


- Constructing scatter plots to identify possible predictors of price in SLR Model
- Showing relationship between indepenndent and dependent variables
- Selecting the best predictor to use as the independent variable in model building 

### Model Building
- Using Stats Models
  - Defining X and y variables 
  - Training SLR model using correct format and .fit( ) method
  - Making predictions using .predict( ) method 
  - Printing key summary statistics using .summary( ) method
  - Plotting residuals to evaluate MLR visually 
- Using Scikit-Learn
  - Defining X and y variables 
  - Performing a train/test split
  - Training SLR model using .fit( ) method 
  - Making predictions using .predict( ) method 
  - Grabbing key summary statistics using .coefficent_ and metrics methods 
  - Plotting residuals to evaluate MLR visually 
