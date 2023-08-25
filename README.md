# Option Pricing using Monte Carlo Simulation

This project, completed during the course EE336: Modeling and Simulation of Stochastic Systems, involved the development of a Python application for pricing European Call and Put Options using Monte Carlo Simulation. The project was carried out from March 2023 to April 2023.

The project repository can be found [here](https://github.com/ayushavi1/Options-Pricing).

## Project Description

The primary goal of this project was to implement a simulation-based approach to calculate the prices of European Call and Put Options. The following steps were taken:

- **Stock Price Prediction**: Our initial approach involved utilizing Linear Regression to predict the returns of HDFC bank in comparison to NIFTY bank returns. However, upon closer examination, we determined that the linear model did not effectively capture the relationship within the past 10 days' data. As a result, we transitioned our approach to a Stochastic Model to better align with the data patterns and achieve more accurate predictions.

- **Monte Carlo Simulation**: Leveraging the Monte Carlo Simulation method, the application calculated the prices of both Call and Put options.

- **Validation with Black-Scholes**: To verify the accuracy of the Monte Carlo simulation, the Black-Scholes formula was utilized to compute the option prices. This provided a basis for comparing and assessing the simulation results.

## Contributors

The project was a collaborative effort, made possible by the contributions of the following individuals:

- [Saksham Kumar](https://github.com/saksham218)
- [Ayush Datta Jaiswal](https://github.com/ayushavi1)
- [Karan Upadhyaya](https://github.com/karanupadhyaya03)

## License

This project is licensed under the [MIT License](LICENSE).
