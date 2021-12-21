# Cryptocurrencies
## Overview of Analysis
The purpose of this project is to use unsupervised machine learning to analyze a data set of cryptocurrencies to generate insights for a marketing company ,Accountability Accounting, who has decided to add cryptocurrencies to its investment portfolio.The goal of this project is to create a report that includes  what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. We have selected unsupervised ML for this project due to the fact that there is still not a know target feature for our analysis.
Below is the steps we took to prepare our results:
a) Processing and cleaning our data
b) Reducing the data dimension using Principal Component Analysis
c) Clustering cryptocurrencies using K-Means
d) Visualizing classification results with 2D and 3D scatter plots.

## Resources
Data Source: https://github.com/farbodjs/Cryptocurrencies/blob/main/Resources/crypto_data.csv
Anaconda 4.10.3, Python 3.8.8, Jupyter Notebook 6.3.0

## Findings

### There is a total of 532 tradable cryptocurrencies that are categorized into 4 Classes.
![image](https://user-images.githubusercontent.com/86033316/146879480-fe10835a-6b22-4343-a84f-5cd16cb82fdb.png)

### Clustering Cryptocurrencies using K-Means - Elbow Curve

![image](https://user-images.githubusercontent.com/86033316/146879794-3683e8f0-879c-4b01-86b5-15b454e4c244.png)
We produced the elbow curve above using the K-Means method iterating on k values from 1 to 10.
We concluded that this data set has k=4 clusters. Therefore, we resumed our analysis with 4 total clusters.

### Visualizing Unsupervised ML 
see below 3-D scatter plot for 4 classes
![image](https://user-images.githubusercontent.com/86033316/146880415-70164dd7-e104-465c-bed3-a776c66738f9.png)
For illustration purposes, we hovered over LiteCoinCash to display Principal Components.

### 2D-Scatter plot with clusters
![image](https://user-images.githubusercontent.com/86033316/146881483-c4f80d57-2b05-4f70-a44a-eb040c10cf3d.png)
Above 2-D scatter plot is created by using the PCA algorithm to reduce the crytocurrencies dimensions to two principal components.
From this plot, we can clearly see that "BitTorrent" which is the only cryptocurreny in class"2" seem to be an outlier or anomoly with only 1 total coin mined.

## Summary

We have identified the classifications of 532 cryptocurrencies based on their "Algorithm" and ""Proof Type". We realized that there is only one coin categorized in Class 2 which was BitTorrent. This groping can help investors understand different cryptocurrencies types and algorithms.
### Future projects

We can extract a data bases that contains the price range and volatilities of these cryptocurrencies along with their trade volumes to describe the investment risks associated with each coin.
