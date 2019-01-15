"#MachineLearning" 

Python programs that implement the K-nearest neighbor and linear regression with gradient descent algorithms. Also included is a linear regression using the sklearn library, this was used to test the accuracy of the manual implementation. Both programs make use of the pandas and numpy libraries.

"##K-Nearest Neighbor"
Implementation of the k-nearest neighbor algorithm on the classic iris dataset. Data is first normalized then the euclidian distance is determined between the sample data and the training data. The distances are sorted in descending order where the nth nearest neighbor is the n+1 index of the list. The list of distances is then used to find the first nearest, top three nearest, and top five nearest neighbors. 

"##Linear Regression with Gradient Descent"
Implementation of the linear regressionon the gradient descent optimization. The data set used contains the following information about cars (in order) mpg, # of cylinders, displacement, horsepower, weight, acceleration. These values are read in via pandas, labeled, then standardized. The theta values are initialized at zero, then continually adjusted to their optimal value.
