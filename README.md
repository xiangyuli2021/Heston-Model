# Heston-Model

Implied Volatility Smile Estimation under Stochastic Volatility Model

•	Estimated the implied volatility smiles (with confidence interval) of put/call options using Monte Carlo simulation via a mixing method based on the Milstein discretization of the variance process, which follows the Heston model
•	Implemented five types of control variates (i.e., the option price using the time-dependent mean of the variance process or deterministic volatility model, the stock price, value of contingent claims dependent on the stochastic variance process, and the combinations of all of the aforementioned financial instruments) to reduce the variance of Monte Carlo simulations for implied volatility smile estimations
