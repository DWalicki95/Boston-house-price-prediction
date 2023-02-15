# Boston-house-price-prediction
8 different regression models to find the best Boston house price prediction

                                                                              
The task is to compare different regression models to predict house prices
in Boston basing on different information like crime rate, nitric oxides
concentration or average number of rooms per dwelling. The challenge was
to test different linear and polynomial regression models.

There were used statsmodels library to fit and evaluate models and their sta-
tistical aspects like relevant and irrelevant features, normal distribution
of data, autocorrelation between rests etc.

Also there were made diagnostic plots (predicted vs true values, residual
charts, qqplots.

Models were prepared also using sklearn library adn their accuracy were
measured.

To sum up, 8 regression  models prepared:
1) Linear model with one explanatory variable
2) Linear model with 4 less variables exluded based on p-value t-student tests
3) Linear model with all variables from dataset
4) Linear model with Ridge regularisation
5) Linear model with Lasso regularisation
6) Polynomial model with all variables
7) Polynomial model with all variables but also with Ridge regularisation
8) Polynomial model with all variables but with Lasso regularisation

The best regression model to predict house price in Boston was polynomial
model with regularisation (and Lasso was sligthly better than Ridge). Models
fit well in the point cloud (~0.91 R^2), were well-adjusted to the data and have low
MSE and MAE on the test set.

