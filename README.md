# Portfolio-Optimization
Portfolio Optimization through Coalescent Employment of Fama French Model & Markowitz Optimization

# Overview

This project presents a comprehensive analysis and optimization of a stock portfolio using the Fama-French model and covariance analysis. The aim is to identify the top-performing companies with minimal correlation to diversify risk and maximize returns. Using a dataset comprising stock prices and returns, we apply the Fama-French three-factor model to calculate expected returns and perform covariance analysis to ensure low correlation among the selected stocks. The portfolio is then optimized using Markowitz's Modern Portfolio Theory.

# Key Contributions

Fama-French Model: Extended the Capital Asset Pricing Model (CAPM) by incorporating three factors: market risk, size risk, and value risk.
Covariance Analysis: Assessed correlations between stocks to ensure portfolio diversification.
Markowitz Optimization: Applied Modern Portfolio Theory to construct an efficient portfolio that maximizes expected return for a given level of risk.
Methodology

## 1. Choosing Companies for Portfolio

Identified 20 companies categorized into big value, small value, big growth, and small growth groups.
Used financial data sources like Bloomberg and Yahoo Finance for historical data collection.
## 2. Historical Data Collection

Gathered one year of historical daily or monthly data for the selected companies.
## 3. Fama-French 3-Factor Model Calculation

Applied the Fama-French model to each company to determine their factor loadings.
## 4. Correlation Matrix Calculation

Computed the correlation matrix for the companies based on their historical returns.
## 5. Filtering Companies Based on Correlation

Selected companies with the least number of correlations less than 0.4 to ensure diversification.
## 6. Ranking Companies by Fama-French Returns

Ranked the filtered companies based on their Fama-French factor returns.
## 7. Final Portfolio Selection

Chose the top 10 companies with the best Fama-French ranks.
## 8. Sharpe Ratio Calculation with Equal Weightage

Evaluated the initial performance of the selected portfolio using equal weights and calculated the Sharpe ratio.
## 9. Markowitz Optimization using Solver

Used Solver to adjust the weights of the 10 companies to maximize the Sharpe ratio.
# Companies Chosen

Laurus Labs: Pharmaceutical company specializing in APIs, formulations, and biotechnology.
Avanti Feeds: Major player in the aquaculture sector, providing high-quality shrimp and fish feed.
Dixon Technologies: Prominent electronics manufacturing services provider in India.
Fine Organic Industries: Leading manufacturer of oleochemical-based additives.
Cera Sanitaryware: Manufacturer of sanitaryware and bathroom products.
KEI Industries: Manufacturer of cables and wires for various industries.
IRCTC: Provides catering, tourism, and online ticketing services for Indian Railways.
Apollo Hospitals: One of the largest healthcare groups in India.
Alkem Laboratories: Pharmaceutical company engaged in the development, manufacture, and marketing of pharmaceutical formulations and nutraceuticals.
Persistent Systems: Global software and technology services company.
Results

# Initial Portfolio Summary with Equal Weightage

Expected Return: 0.5376
Standard Deviation: 16.70%
Sharpe Ratio: 2.81
Optimized Portfolio Summary

Expected Return: 0.5771
Standard Deviation: 15.16%
Sharpe Ratio: 3.35
Optimal Weights

Avantifeed: 10%
Fine: 5%
Kei: 10%
Irctc: 5%
Persistent: 35%
Heidelberg: 15%
Deepak: 5%
Hdfc: 10%
Balaji: 5%
Apollo: 5%
# Conclusion

The integrated use of the Fama-French model, covariance analysis, and Markowitz optimization creates a robust framework for portfolio optimization. This approach ensures a well-diversified portfolio that balances the trade-off between risk and return, ultimately enhancing the investment strategy's efficiency and effectiveness. The optimized portfolio demonstrates a higher Sharpe ratio, indicating better risk-adjusted returns.

# Authors

Sricharan Sridhar (20MIA1014)
Nikitha A R (20MIA1025)
