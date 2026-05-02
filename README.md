# Tse_Portfolio_Optimization_MPT
Portfolio optimization of selected Tehran Stock Exchange stocks using Random Portfolios, Modern Portfolio Theory (MPT), SciPy optimization, and Efficient Frontier analysis.
Tehran Stock Exchange Portfolio Optimization (MPT)
This project analyzes and optimizes a portfolio of selected stocks from the Tehran Stock Exchange (TSE) using Modern Portfolio Theory (MPT).

The workflow is implemented in a single Jupyter Notebook and includes random portfolio generation, Sharpe ratio analysis, and numerical optimization using SciPy.

All price data is retrieved dynamically using the finpy_tse library.

Stocks Analyzed
The following six stocks are included in the portfolio:

دکپسول
فولاد
ثشرق
سپیدار
سصوفی
تپسی
Time Period
01-01-1399 → 29-12-1402

Daily adjusted closing prices are used for the analysis.

Project Workflow
The notebook performs the following steps:

Data collection from Tehran Stock Exchange using finpy_tse
Data preprocessing and return calculation
Price normalization and exploratory visualization
Random portfolio weight generation
Monte Carlo simulation of portfolios
Risk and return calculation
Sharpe ratio analysis
Portfolio optimization using scipy.optimize
Efficient frontier construction
Visualization of optimal portfolios and risk-return tradeoff
Tools and Libraries
The project uses the following Python libraries:

NumPy
Pandas
Matplotlib
Plotly
SciPy
finpy_tse
pandas-datareader
How to Run
Clone the repository:

git clone https://github.com/YOUR_USERNAME/tse-portfolio-optimization-mpt.git

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook

Open:

MPT.ipynb

Output
The notebook produces:

Normalized price charts
Portfolio return and volatility calculations
Sharpe ratio analysis
Monte Carlo portfolio distribution
Maximum Sharpe ratio portfolio
Optimized portfolio using SciPy
Efficient frontier visualization
Disclaimer
This project is created for educational purposes and should not be considered financial advice.
