# PortfolioOptimization-and-CAPM

This project is about computing and optimizing the expected returns of a portfolio of equity stocks.
We are going to build a small and simple portfolio using Yahoo Finance's historical close prices in order to:
- Simulate a portfolio optimization and the best weights assignment starting from a Markovitz implementation to compute the expected returns and risks
- Develop a CAPM using SP&500 as the market reference and study two different versions of estimating the Beta parameter

The first point will focus on:
- Computing expected returns and risks using the annualized returns' historical trends and the covariance between the stocks considered
- Simulating n-thousands of potential portfolios by randomly generating different sets of weights that represent the % of our investment in each stock composing our portfolio.
- Computing the Sharpe Ratio to evaluate the performance of each portfolio against a hypothetical risk-free asset return of 3%
- Identifying the best weight to assign to each stock in the portfolio (hence the most efficient portfolio) using an optimization function to maximize the Sharpe Ratio value.

  The second point will focus on:
- Evaluating Beta as the ratio of the Covariance between each stock and the market and the variance of the market itself
- Evaluating Beta using a linear regression model
- Analyzing the difference between the two methods
- Evaluating the annualized expected returns and risks of a portfolio given a set of weights

  Thank you!
