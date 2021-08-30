# Module_Eighteen_Cryptocurrencies

## Project Overview
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked for a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. Since there is no known output for what Accountability Accounting is looking for, we will use unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm. We'll use data visualizations to share the findings with the board.

## Resources
 - Data Source: [crypto_data.csv]()
 - Software: Python, Anaconda, Conda, Jupyter Notebook, Sklearn

## Results

Clustering Cryptocurrencies using K-Means - Elbow Curve:
 - The best k value is 4 so it's best to output of 4 clusters to categorize cryptocurrencires.
![Elbow Curve](https://github.com/LLeyva-bot/Cryptocurrencies/blob/main/Images/Fig1.png)

3D-Scatter Plot with Clusters to Visualize Cryptocurrencies Results:
 - The 3D-scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.
![3DScatter Plot](https://github.com/LLeyva-bot/Cryptocurrencies/blob/main/Images/Fig2.png)

Tradable Cryptocurrencies Table:
 - A majority of the cryptocurrencies are part of class '0' and '1'.
![Tradable Table](https://github.com/LLeyva-bot/Cryptocurrencies/blob/main/Images/Fig4.png)

2D-Scatter plot with Total Coin Mined vs Total Coin Supply:
![2DScatter Plot](https://github.com/LLeyva-bot/Cryptocurrencies/blob/main/Images/Fig3.png)

## Summary
We identified the classification of 532 cryptocurrencies based on mining and supply data which limited the classification model. Cryptocurrency trading volume, price, mining rate, accessibility, and market share could add data points to further define the clusters and provide further insight. 
