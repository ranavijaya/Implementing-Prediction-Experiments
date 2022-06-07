# **Implementing Prediction Experiments**

## Initial set Up

We used data from [this paper](https://ojs.aaai.org/index.php/ICWSM/article/view/7355). The data is a collection of reviews from [Pitchfork](https://pitchfork.com/), a site that provides expert reviews of music album. The authors of this paper have also combined the data with a set of features from [Spotify’s API](https://developer.spotify.com/documentation/web-api/) that provide insight into the music itself, e.g. the "acousticness" of the song. 

We tackled a regression problem here, trying to predict the score of a review from several of the other columns in the dataset.

## Tasks Performed
#### Part 1.1 - Feature Engineering with Feature Subsets
#### Part 1.2 - Feature Engineering with the LASSO
#### Part 1.3 - Interpreting Model Coefficients
#### Part 1.4 - "Manual" Cross-Validation + Holdout for Model Selection and Evaluation
#### Part 2.1 - Logistic Regression with Gradient Descent
#### Part 2.2 - Optimization with Newton-Raphson

## Summary 

1.We write code to train and evaluate models using both the two-way holdout method, and an evaluation approach appropriate for models with hyperparameters that uses k-fold cross validation plus a test set.
2.Optimized a machine learning model. We use gradient descent to optimize a logistic regression model.
3.Additionally, we Perform optimization with a different algorithm (Newton-Raphson)
