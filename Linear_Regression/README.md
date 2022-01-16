
<h1>Gradient Descent For Linear Regression</h1> 

Gradient descent is an iterative optimization algorithm to find the minimum of a function. Here that function is our Loss Function.





<h3>Algorithm</h3>
Check this link out
https://towardsdatascience.com/linear-regression-using-gradient-descent-97a6c8700931



The point of all this is that if we start with a guess for our hypothesis and then repeatedly apply these gradient descent equations, our hypothesis will become more and more accurate.

So, this is simply gradient descent on the original cost function J. This method looks at every example in the entire training set on every step, and is called batch gradient descent. Note that, while gradient descent can be susceptible to local minima in general, the optimization problem we have posed here for linear regression has only one global, and no other local, optima; thus gradient descent always converges (assuming the learning rate α is not too large) to the global minimum.

Indeed, J is a convex quadratic function. Here is an example of gradient descent as it is run to minimize a quadratic function.




1. **m** = Number of the data set

2. **h(x)** = theta0 + theta1 * x 

3. X is list of inputs / Features

4. Y is list of output
 

 