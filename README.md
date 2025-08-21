# Black-Scholes-Merton-Model-in-Python

Project Objective-

To build a Black-Scholes-Merton (BSM) Option Pricing Model that computes European Call and Put option values, derives option Greeks (Delta, Gamma, Vega, Theta, Rho), estimates implied volatility, and validates option pricing using Monte Carlo simulation.
The project demonstrates how a fundamental FRM concept is applied in practice for valuation and risk management.

Methodology - 

Input Parameters: Load option parameters including spot price, strike price, maturity, volatility, risk-free rate, and dividend yield.
Closed-form Solution: Implement Black-Scholes-Merton equations for Call and Put options.
Greeks Calculation: Compute risk sensitivities (Delta, Gamma, Vega, Theta, Rho).
Implied Volatility: Apply bisection search to back-solve volatility from observed option prices.
Monte Carlo Simulation: Simulate asset price paths under risk-neutral dynamics to compare simulated option prices with analytical values.
Validation: Check Put-Call Parity and convergence of Monte Carlo results.
Visualization: Plot payoff diagrams, option price vs. strike, and Greeks vs. volatility for deeper understanding.


Conclusion - 

This project demonstrates practical application of the Black-Scholes-Merton Model for option valuation and risk management.
For FRM candidates: It reinforces core concepts from Market Risk, Derivatives, and Valuation.
For practitioners: It shows how to compute fair values, Greeks for hedging, and implied volatility for calibration.
For risk managers: It highlights how sensitivities guide hedging strategies and how Monte Carlo validation supports model risk management.
By integrating analytical formulas, numerical simulation, and visualization, this project connects theory with practice—aligning with the quantitative rigor expected in FRM roles.
