# Regression

## Decision-Tree-Regression
Using Decision Tree predict salary based on dataset(Position-level)
It is simple Decision Tree regressor model where data is non-continuous.(non-linear)

How dicision tree work for regrassion:

**1**   Make some splits on the dataset based on information entropy(basically dividing the points into some groups).Here,algorithm can decides the optimal number of splits and then splits the dataset accordingly them.

**2**   Algorithm will take the average value of each group and based on that values it will build the decision tree for this dataset.


## Random Forest Regression
**1**   Boosting: Boosting is a technique that boosts the learning by grouping individual weak learners to form a single strong learner It is a sequential process, where each subsequent model attempts to correct the errors of the previous model. Here, The succeeding models are dependent on the previous model.

**2**   Bootstrap Aggregation: Bootstrapping is a sampling technique in which we create subsets of observations from the original dataset. also referred to as Bagging. here size of the subsets used is the same as that of the original set. So,The size of subsets created for bagging may be less than the original set.

## Support Vector Regression

**1**   upport Vector Regression in basically trying to decide a decision boundary at E(means boundary line) distance from the original hyper plane such that data points closest to the hyper plane or the support vectors are within that boundary line.

## Multivariate regression

**1**   we have to select one feature that drives the multivariate regression. even This  feature  is highly responsible for the change in our dependent variable. 

**2**   Secondly, scale feature in a certain range (0-1 preferably) so that can analysing them gets a easy.

**3**   then, use formulated hypothesis (predicted value of the response variable (noted= h(x)) )
    Also, use loss function (calculate loss when the hypothesis predicts a wrong value)

**4**   after then Minimize the cost and loss function . Well One of the minimization algorithms that can be used is the gradient descent algorithm.

**5**   in last Test the hypothesis (Hypothesis is then tested with a test set to check its accuracy and correctness.)

## 
## However, there are some pros and cons of Regression.

![regression pros_cons](https://user-images.githubusercontent.com/59303032/168262235-273a0bd8-56c5-4cc7-a375-3c9381ea319d.JPG)

