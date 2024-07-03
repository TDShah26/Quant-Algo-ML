# Quant-Algo-ML

## Overview
Quant-Algo-ML is a project aimed at implementing quantitative trading algorithms using machine learning techniques. The project focuses on analyzing and trading NIFTY indices, including NIFTY 100, NIFTY 500, NIFTY Midcap 100, and NIFTY Midcap 150.

## Features
- **Quantitative Analysis**: Detailed analysis of NIFTY indices.
- **Machine Learning Integration**: Utilizes various machine learning models for trading decisions.
- **Data Processing**: Processes historical data for accurate predictions.
- **Interactive Notebooks**: Jupyter notebooks for each NIFTY index with step-by-step code.

## Usage
1. Open the Jupyter notebooks in the repository:
    - NIFTY100_QuantAlgo.ipynb
    - NIFTY500_QuantAlgo.ipynb
    - NIFTYMidcap100_QuantAlgo.ipynb
    - NIFTYMidcap150_QuantAlgo.ipynb
2. Run the cells to process data, train models, and make trading predictions.

## Project Workflow
1. **Download/Load NIFTY Stock Prices Data**: Load stock prices for NIFTY 500, NIFTY 100, NIFTY Midcap 100, and NIFTY Midcap 150.
2. **Feature and Indicator Calculation**: Compute various financial features and indicators for each stock.
3. **Monthly Aggregation and Filtering**: Aggregate data on a monthly level and filter the top 150 most liquid stocks.
4. **Monthly Returns Calculation**: Calculate monthly returns for different time horizons.
5. **Fama-French Factors**: Download Fama-French factors and calculate rolling factor betas.
6. **K-Means Clustering**: Apply K-Means clustering algorithm monthly to group similar assets based on their features.
7. **Portfolio Selection**: Select assets based on the cluster and form a portfolio using Efficient Frontier max Sharpe ratio optimization.
8. **Visualization**: Visualize portfolio returns and compare them to respective index fund returns.

## Technologies Used
- **Python**: Programming language for algorithm development.
- **Jupyter Notebook**: Interactive notebooks for code and visualization.
- **Pandas**: Data manipulation and analysis.
- **Scikit-learn**: Machine learning library for model training.
- **Matplotlib/Seaborn**: Data visualization libraries.

## Code Comments
- All code in this repository has been commented line by line to enhance understanding and readability.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
- Special thanks to the open-source community for the resources and tools.
- This repository is inspired by and uses resources from [Algorithmic Trading Machine Learning Quant Strategies](https://github.com/Luchkata/Algorithmic_Trading_Machine_Learning/blob/main/Algorithmic_Trading_Machine_Learning_Quant_Strategies.ipynb).
