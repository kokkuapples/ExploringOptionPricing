# Exploring Option Pricing

The scope of this notebook is to explore various methodologies to price european and american options using Monte Carlo methods. Specifically, we exploit the risk-neutral framework to price european call options and validate the result using the Black-Scholes formula as a benchmark. 

Also, we test the constant volatility assumption of the B.S. by computing the implied volatility across strikes at fixed maturity, showing a volatility smile.

In the second part, we price american put options using the [Longstaff-Schwartz algorithm](https://people.math.ethz.ch/~hjfurrer/teaching/LongstaffSchwartzAmericanOptionsLeastSquareMonteCarlo.pdf) (Least Squares Monte Carlo), which accounts for early exercise. 

Each part is supported by a brief theoretical introduction to illustrate the mathematics and justify what is behind the code. 
