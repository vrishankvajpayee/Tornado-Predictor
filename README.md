# Tornado-Predictor
Using python libraries such as numpy and pandas for the prediction of random variables.
Well we can use the binomial distribution in NumPy to simulate this.
Here we create an empty list and we create a number of potential tornado events by 
asking the NumPy binomial functions using our chance of tornado. 


This process is called sampling the distribution.
Now we can write a little loop to go through the list and look for any two adjacent pairs of ones which means that there were 
two days that had back to back tornadoes. 
We see that this ends up being roughly 90 day tornado events over the 3,000 years. 
 
My point here though is that modern computational power allows us to very quickly simulate the effects of different parameters in a distribution.
Leading to a new way of understanding the problem. 
You don't have to work out all the math you can quite often simulate the problem instead and observe the results.

