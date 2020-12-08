# housing-analysis
prediction of prices for Melbourne
the data is available in kaggle please access through link:-https://www.kaggle.com/anthonypino/melbourne-housing-market
i haven't done split code you can parse html to ipynb and run with data 

#from analyticsvidhya

https://analyticsindiamag.com/why-is-random-search-better-than-grid-search-for-machine-learning/


# Grid Search


Grid search is a technique which tends to find the right set of hyperparameters for the particular model. Hyperparameters are not the model parameters and it is not possible to find the best set from the training data. Model parameters are learned during training when we optimise a loss function using something like a gradient descent. In this tuning technique, we simply build a model for every combination of various hyperparameters and evaluate each model. The model which gives the highest accuracy wins. The pattern followed here is similar to the grid, where all the values are placed in the form of a matrix. Each set of parameters is taken into consideration and the accuracy is noted. Once all the combinations are evaluated, the model with the set of parameters which give the top accuracy is considered to be the best. Below is a visual description of uniform search pattern of the grid search.
