# Bayesian_LinearRegression

Bayesian regression is a type of linear regression that uses Bayesian statistics to estimate the unknown parameters of a model. It uses Bayes’ theorem to estimate the likelihood of a set of parameters given observed data. The goal of Bayesian regression is to find the best estimate of the parameters of a linear model that describes the relationship between the independent and the dependent variables.

The main difference between traditional linear regression and Bayesian regression is the underlying assumption regarding the data-generating process. Traditional linear regression assumes that data follows a Gaussian or normal distribution, while Bayesian regression has stronger assumptions about the nature of the data and puts a prior probability distribution on the parameters. Bayesian regression also enables more flexibility as it allows for additional parameters or prior distributions, and can be used to construct an arbitrarily complex model that explicitly expresses prior beliefs about the data. Additionally, Bayesian regression provides more accurate predictive measures from fewer data points and is able to construct estimates for uncertainty around the estimates. 

## Advantages of Bayesian Regression: 

- Very effective when the size of the dataset is small.
- Particularly well-suited for on-line based learning (data is received in real-time), as compared to batch-based learning, where we have the entire dataset on our hands before we start training the model. This is because Bayesian Regression doesn’t need to store data.
- The Bayesian approach is a tried and tested approach and is very robust, mathematically. So, one can use this without having any extra prior knowledge about the dataset.
- Bayesian regression methods employ skewed distributions that let you include outside information in your model.
- Bayesian regression can handle outliers and influential observations more effectively compared to classical regression methods. It provides a more robust approach to regression analysis, as extreme or influential observations have a lesser impact on the estimation.

## Disadvantages of Bayesian Regression:  
- The inference of the model can be time-consuming.
- If there is a large amount of data available for our dataset, the Bayesian approach is not worth it and the regular frequentist approach does a more efficient job
- If your code is in a setting where installing new packages is challenging and there are strong dependency controls, this might be an issue.
- Many of the basic mistakes that commonly plague traditional frequentist regression models still apply to Bayesian models. For instance, Bayesian models still depend on the linearity of the relationship between the characteristics and the outcome variable.

## When to use Bayesian Regression:
- **Small sample size:** When you have a tiny sample size, Bayesian inference is frequently quite helpful. Bayesian regression is a wonderful choice if you need to develop a very complicated model but do not have access to a lot of data. In fact, it’s probably the greatest choice you have! Large sample sizes are necessary for many other machine-learning models to work properly.
- **Strong prior knowledge**: The easiest method to include strong external knowledge into your model is by utilising a Bayesian model. The influence of the prior knowledge will be more obvious the smaller the dataset size you work with.
