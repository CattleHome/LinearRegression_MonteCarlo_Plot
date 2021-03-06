Introduction: This is a course project, which consists of 5 parts. 

Contents: simple & multiple linear regression, Monte Carlo simulation, plotting of line/curve/scatter/bar, bisection.

Programming Language: Python

Part 1:

Industry_Portfolios.xlsx contains monthly returns for a portfolio of 10 industries. First, calculate mean, standard deviation and covariance matrix for the portfolio. Second, plot 2 minimum-variance frontiers without riskless asset and with riskless asset respectively. The 2 frontiers intersect at a single point which leads to the tangency portfolio with the highest Sharpe ratio.

Part 2:

Market_Portfolio.xlsx contains monthly returns for the market portfolio. This part mainly applies linear regression method. First, regress monthly returns for each industry on monthly return for the market portfolio, and generate intercept and slope coefficients for each industry. Second, regress mean returns for each industry on slopes for each industry, in order to obtain intercept and slope coefficient for SML (Security Market Line). Third, plot SML and mean returns for 10 industries. The points above SML are underpriced, while the points below SML are overpriced.

Part 3:

First, generate performance metrics of Sharpe ratio, Sortino ratio, Jensen's alpha, and Three-Factor alpha. Among those, Jensen's alpha and Three-Factor alpha are generated by applying simple and multiple linear regression respectively. Second, generate 10 numbers from uniform distribution and divide each number by the sum of the 10 numbers, in order to obtain weights of each industry which ensures total weight to be 1. Calculate mean and standard deviation of the portfolio. By applying Monte Carlo simulation, repeat this process for 10,000 times and plot scattered points.

Sharpe ratio represents risk premium per unit of total risk. Sortino ratio represents risk premium per unit of downside risk. Jensen's alpha represents abnormal return after adjusting for exposure to market risk. Three-factor alpha represents abnormal return after adjusting for exposure to market risk, size risk, and value risk.

Part 4:

Generate 1,000 inputs from standard normal distribution and uniform distribution, calculate the respective outputs within a range based on formulae, and plot.

Part 5:

Define a bisection definition to obtain the root of a formula.
