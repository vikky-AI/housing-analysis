# housing-analysis
prediction of prices for Melbourne
the data is available in kaggle please access through link:-https://www.kaggle.com/anthonypino/melbourne-housing-market
i haven't done split code you can parse html to ipynb and run with data 

# from analyticsvidhya

https://analyticsindiamag.com/why-is-random-search-better-than-grid-search-for-machine-learning/


# Grid Search


Grid search is a technique which tends to find the right set of hyperparameters for the particular model. Hyperparameters are not the model parameters and it is not possible to find the best set from the training data. Model parameters are learned during training when we optimise a loss function using something like a gradient descent. In this tuning technique, we simply build a model for every combination of various hyperparameters and evaluate each model. The model which gives the highest accuracy wins. The pattern followed here is similar to the grid, where all the values are placed in the form of a matrix. Each set of parameters is taken into consideration and the accuracy is noted. Once all the combinations are evaluated, the model with the set of parameters which give the top accuracy is considered to be the best. Below is a visual description of uniform search pattern of the grid search.


# Random search
Random search is a technique where random combinations of the hyperparameters are used to find the best solution for the built model. It is similar to grid search, and yet it has proven to yield better results comparatively. The drawback of random search is that it yields high variance during computing. Since the selection of parameters is completely random; and since no intelligence is used to sample these combinations, luck plays its part.

As random values are selected at each instance, it is highly likely that the whole of action space has been reached because of the randomness, which takes a huge amount of time to cover every aspect of the combination during grid search. This works best under the assumption that not all hyperparameters are equally important. In this search pattern, random combinations of parameters are considered in every iteration. The chances of finding the optimal parameter are comparatively higher in random search because of the random search pattern where the model might end up being trained on the optimised parameters without any aliasing


# Mahalnobis diatance
Generally, variables (usually two in number) in the multivariate analysis are described in a Euclidean space through a coordinate (x-axis and y-axis) system. Suppose if there are more than two variables, it is difficult to represent them as well as measure the variables along the planar coordinates. This is where the Mahalanobis distance (MD) comes into picture. It considers the mean (sometimes called centroid) of the multivariate data as the reference.
The MD measures the relative distance between two variables with respect to the centroid. Therefore, farther the variable is from the centroid, the larger the MD is.

# Standard deviation-

The standard deviation is a statistic that measures the dispersion of a dataset relative to its mean and is calculated as the square root of the variance

# One hot encoding- 

For categorical variables where no ordinal relationship exists, the integer encoding is not enough.
In fact, using this encoding and allowing the model to assume a natural ordering between categories may result in poor performance or unexpected results (predictions halfway between categories).
In this case, a one-hot encoding can be applied to the integer representation. This is where the integer encoded variable is removed and a new binary variable is added for each unique integer value.
Disadvantages of decision tree
•	Decision trees are prone to overfitting
•	Gives most optimal solution but not globally optimal solution
•	Decision trees do not have same predictive accuracy compared to other regression and classification models
We use another algorithm called Random Forest to overcome the disadvantages of decision tree.

# What is Random Forest?

Let’s say you are asked to estimate how many candies are there in the jar. you need to do this without opening the jar.
You can ask different people to estimate for you and then if you take an average of all the different estimates, you will be very close the actual count.
This is exactly how random forest works. Random Forest increases predictive power of the algorithm and also helps prevent overfitting.

Random forest is the most simple and widely used algorithm. Used for both classification and regression. It is an ensemble of randomized decision trees. Each decision tree gives a vote for the prediction of target variable. Random forest choses the prediction that gets the most vote.


