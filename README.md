# Crypto Clustering
## Case study
A Financial Advisory firm is looking for a new way of constructing investment portfolios based on cryptocurrencies. 

This is a prototype to trial an approach that considers not only returns and volatility, but also other factors that 
might impact the crypto market. The prototype is presented as a [Jupyter Lab notebook](crypto_investments.ipynb).

## Data sources
- Price change data of some cryptocurrencies in different periods: [crypto_market_data.csv](Resources/crypto_market_data.csv)

## Tasks to support the Analysis of the data
* Importing and preparing the data.
* Find the best value for k by using the original data.
* Clustering of cryptocurrencies with K-means by using the original data.
* Optimising the clusters with principal component analysis.
* Finding the best value for k by using the PCA data.
* Clustering the cryptocurrencies with K-means by using the PCA data.
* Plotting the results to compare the performance of the clusters visually.


## Technical Environment
This tool utilises the following technologies:
- **Pandas** DataFrame: [Documentation](https://pandas.pydata.org/docs/reference/frame.html)
- **hvplot** Bar chart, Line plot, Scatter:  [Documentation](https://hvplot.holoviz.org/getting_started/hvplot.html)
- **sklearn** Cluster, decomposition, preprocessing:  [Documentation](https://scikit-learn.org/stable/)

## Disclaimer
> Please be aware this is an Academic Case Study. The conclusions from this work should not be considered as financial 
> advice.