θ - theta

Cost Function - Intuition I
If we try to think of it in visual terms, our training data set is scattered on the x-y plane. 
We are trying to make a straight line ( defined by hθ(x) ) which passes through these scattered data points.

ur objective is to get the best possible line. 
The best possible line will be such so that the average squared vertical distances of the scattered points from the line will be the least. 
Ideally, the line should pass through all the points of our training data set. 
In such a case, the value of J(theta0, theta1)  will be 0. The following example shows the ideal situation where we have a cost function of 0.

![image1](image1.png) 

When theta_1=1 , we get a slope of 1 which goes through every single data point in our model. Conversely, when theta_1=0.5, 
we see the vertical distance from our fit to the data points increase.

![image2](image2.png) 

This increases our cost function to 0.58. Plotting several other points yields to the following graph:

![image3](image3.png)

Thus as a goal, we should try to minimize the cost function. In this case, theta_1=1 is our global minimum.
