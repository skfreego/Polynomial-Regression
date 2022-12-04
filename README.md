### Predict Salary using Polynomial Regression 

## Objective
	To build a model to predict what salary we should offer this new employee.

#### Fit Linear Regression model to dataset
	First we will build a simple Linear Regression model to see what prediction it makes and then compare it to the prediction made by the Polynomial Regression to see which is more accurate.
We create an object of the LinearRegression class and call the fit method passing the X and y.

#### Convert X to polynomial format
	For Polynomial Regression, we need to transform our matrix X to X_poly where X_poly will contain X to the power of n — depending upon the degree we choose.
If we choose degree 2, then X_poly will contain X and X to the power 2.

If we choose degree 3, then X_poly will contain X, X to the power 2 and X to the power 3.

	When we create an object of this class — we have to pass the degree parameter.
Let’s begin by choosing degree as 2. Then we call the fit_transform method to transform matrix X.

#### Fitting Polynomial Regression	
	Now we will create a new linear regression object called lin_reg_2 and pass X_poly to it.

Let’s increase the degree one more time to 4 and see if the prediction gets better or worse.


