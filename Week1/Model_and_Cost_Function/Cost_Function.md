# Cost Function

<strong>We</strong> can measure the accuracy of our hypothesis function by using a cost function. This takes an average difference (actually a fancier version of an average) of all the results of the hypothesis with inputs from x's and the actual output y's.

![Cost Function](Cost_Function.png) <br>

<strong>To</<strong> break it apart, it is 1/2 x̅ where x̅ is the mean of the squares of h_\θ(x_i) - y_i //θ - theta or the difference between the predicted value and the actual value.
This function is otherwise called the "Squared error function", or "Mean squared error". The mean is halved (1/2)
as a convenience for the computation of the gradient descent, as the derivative term of the square function will cancel out the 1/2
term. The following image summarizes what the cost function does:

![Cost Function](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/R2YF5Lj3EeajLxLfjQiSjg_110c901f58043f995a35b31431935290_Screen-Shot-2016-12-02-at-5.23.31-PM.png?expiry=1609891200000&hmac=F7xQfH6b2KSiEKjiW4kQqup0Wx6MykpcEBDx-VPozMU)

