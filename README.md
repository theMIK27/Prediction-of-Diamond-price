# Prediction-of-Diamond-price
Step 1: Understanding the Model 
1.	According to the model, if a diamond is 1 carat heavier than another with the same cut, how much more should I expect to pay? Why?

		As given formula, the amount of carat is multiplied by 8413. So, if a diamond is 1 carat heavier than another with the same cut, I should expect to pay $ 8413 more.

2.	If you were interested in a 1.5 carat diamond with a Very Good cut (represented by a 3 in the model) and a VS2 clarity rating (represented by a 5 in the model), how much would the model predict you should pay for it?

		Prediction of price by model
		= -5269+8413*carat+158.1*cut ord+454*clarity ord
		= -5269+8413*1.5+158.1*3+454*5
		=10194.8
		By prediction of the model, I should pay 10194.8 USD.


Step 2: Visualize the Data 

1.	Plot 1 - Plot the data for the diamonds in the database, with carat on the x-axis and price on the y-axis. 
2.	Plot 2 - Plot the data for the diamonds for which you are predicting prices with carat on the x-axis and predicted price on the y-axis. 

		I have plotted both sets of value in one scatterplot in different colors.

3.	What strikes you about this comparison? After seeing this plot, do you feel confident in the model’s ability to predict prices? 

		•	The prediction seems not reliable in some situations. Of course, the model is taking carat, cut and clarity into account but there       are many factors which will affect the price of diamond. Such factors are color, shape, ongoing trend and many more.

		•	How can prices be negative for diamonds? It seems that converting cut and clarity into numbers is not a good approach.

		•	Predicted prices are distributed linearly but old diamond prices are nonlinear.

		•	From all the observation, it seems that linear regression is not the best method to predict the price for diamonds.


Step 3: Make a Recommendation
1.	What price do you recommend the jewelry company to bid? Please explain how you arrived at that number.

		I recommend the company to bid no more than $8,213,465.93. 

		By using the formula from the regression model which was based on the previous diamond sales and applied that to the diamonds that 			were up for bid. Since the company generally purchases diamonds from sellers at 70% of that price.

		So,
		Predicted amount = Sum of all predicted price * (0.7)
                             = $ 11,733,522.76 * (0.7)
                             = $ 8,213,465.93

