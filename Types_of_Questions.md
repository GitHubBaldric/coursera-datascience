## Type of Data Science Questions

### Descriptive
	* GOAL: Describe a set of data
	* Commonly applied to census data
	* Usually not generalized without additional statistical modelling
	* EXAMPLE: Census data
### Exploratory
	* GOAL: Find relationships you didn't know about
	* Useful for defining future studies
	* Not the final say
	* Not used for generalizing or predicting
	* EXAMPLE: Brain response in response to specific stimulus
### Inferential
	* GOAL: Use a relatively small sample of data to say something about a bigger population
	* Commonly the goal of statistical models
	* Involves estimating both the quantity you're interested in AND your uncertainty about your estimate
	* Depends highly on both the population and sampling scheme
	* EXAMPLE: Effect of Air Pollution Control on Life Expectancy in the United States
### Predictive
	* GOAL: Us the data on some objects to predict values for another object
	* X predicts Y != X causes Y
	* Depends heavily on measuring the correct variables
	* More data and a simple model works well
	* Prediction is hard
	* EXAMPLE: fivethirtyeight.blogs.nytimes.com | Predict outcomes of elections.
### Causal 
	* GOAL: to find out what happens to one variable when you make another variable change
	* Randomized studies are usually required
	* Approaches to inferring causation in non-randomized studies are complicated and sensitive to assumptions
	* Usually identified as average effects, but may not apply to every individual
	* "Gold Standard" for data analysis
	* EXAMPLE: Faecal Transplants - randomized people who got this treatment and determined this treatment was causally associated with better outcomes
### Mechanistic
	* GOAL: To understand the exact changes in variables that lead to changes in other variables for individual objects
	* Incredibly hard to infer
	* Usually modelled by a deterministic set of equations
	* Generally the random component of the data is measurement error
	* If the equations are known but the parameters are not, they may be inferred with data analysis
	* EXAMPLE: What are specific changes in pavement design to result in desired changes in pavement performance.