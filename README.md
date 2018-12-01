# Black-Scholes-Calculator
Simple implied volatility calculator for vanilla options using Newton-Raphson formula

The Black-Scholes option pricing model provides a closed-form pricing formula BS(σ) for a European-exercise option with price P. There is no closed-form inverse for it, but because it has a closed-form vega (volatility derivative) ν(σ), and the derivative is nonnegative, we can use the Newton-Raphson formula. This only works for options where the Black-Scholes model has a closed-form solution and a nice vega. When it does not, as for exotic payoffs, American-exercise options and so on, we need a more stable technique that does not depend on vega. In these harder cases, it is typical to apply a secant method with bisective bounds checking.
