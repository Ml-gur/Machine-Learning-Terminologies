# Machine-Learning-Terminologies
- Observation- this is a single collection  of predictors and target variables. 
   - A target variable can also be termed as output variable and refers to the variables we #INTEND to #Model. Target variables are DEPENDENT
   - for you to model the target variables, you use #INPUT VARIABLES also known as predictors or features. Input variables are INDEPENDENT

- Dataset- this involves multiple observations with same variables that are put together

	- there are three kinds of dataset namely:
		
			- Training Dataset - this is the dataset that is used to build a machine learning model
			-  the training dataset is assumed to always have N observations and D number of predictors
			-  the vector features for nth observation is denoted by Xn meaning that Xn include the functions in th original predictors. 			
		- Validation Dataset- this is the dataset that is used when comparing multiple models 
		  that have been built on same training dataset using different parameters
		- Testing Dataset- the dataset that is used to evaluate the final perfomance of the model
		- 


- Variable types
		- variables can either be categorical or quantitative:
				- Quantitative show a continuous or almost-continuous scale an example is the height of a person. 
				- Categorical are based on a discrete set of group
				
							
		- if the variables are quantitative then the modeling task is refered to as #Regression
		- while if te target is categorical the modeling is refered to as #classification
		

# Modeling Structure
			
 # Linear Regression
 	we will denote it as LR
- Linear Regression is used to understand the relationship between input/predictors and output/targets numerical variables.
	- since it is a # Model, the model assumes that there is a linear relationship between a given input variable (x) and a single target variable (y). 
	- the target variable (y) is calculated from the Linear Combination of input variable (x). 
- Types of linear regression:

		- Simple Linear Regression - this is a type of regression when there is a single predictor variable (x)
			Representation:  
				y = B0 + B1*x
				
		- Multiple regression - this is when there are multiple predictor variables (x)
	
- it is both a statistical and machine learning algorithm
- LR is represented as a linear equationthat combines the predictor variables (x) soution to a target variable (y) of the input variable. 

		the input and output remain numeric

- the Linear Equation will assign a scale factor of the input value termed as #Coefficient and represented by Beta symbol (B). 
- Adding another coefficient to the equation gives it a degree of freedom allowing it to move up and down on a two-dimensional plot.
- this two dimensional plot is termed as #intercept or the bias coefficient. 

			the LR target variable (y) follows a linear function if one or multiple predictor variables (x1,...xD) plus some random error
			Assuming we have a model with nth Observation, our Eqn will be as follows:
				yn = β0 + β1xn1 + ⋯ + βDxnD + ϵn.
				
			the  β0 refers to the intercept term,  β1 all through to BD are the coefficients added on the feature variables
			ϵ is the error
			
- the LR Eqn can be represented by vectorizing the predictors and their cefficients
		
		Xn = ( 1 xn1 ... xnD)T
		β = (β0 β1 ... βD)T
		
		the 1 in Xn corresponds to the intercept β0. through the above eqn we can express (yn ) as the following:
		
			yn = β⊤xn + ϵn
			
