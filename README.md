# Cryptocurrencies

## Overview
I was tasked with creating a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.  Unsupervised machine learning was the model utilized in this analysis.

Deliverables:
- Deliverable 1: Preprocessing the Data for PCA
- Deliverable 2: Reducing Data Dimensions Using PCA
- Deliverable 3: Clustering Cryptocurrencies Using K-means
- Deliverable 4: Visualizing Cryptocurrencies Results

## Technology Used & Resources:
- Python
- Jupyter Notebook
- crypto_data.csv

## Results:
I utilized the code initially outlined in the crypto starter file provided; I added additional code to complete the [crypto_clustering.ipynb](https://github.com/Jahill17/Cryptocurrencies/blob/main/crypto_clustering.ipynb) file.


**The first deliverable required preprocessing the data for PCA. See the below screenshot for the results**

![This is an image](https://github.com/Jahill17/Cryptocurrencies/blob/main/ScreenGrabs/Deliv1_CreateVariables_StdScaler.png)


**The second deliverable required reducing the data dimensions using PCA**

![This is an image](https://github.com/Jahill17/Cryptocurrencies/blob/main/ScreenGrabs/Deliv2_PrincipalComponents.png)
- The above is a created DataFrame with the three principal components.


**The third deliverable required clustering cyrptocurrencies using K-means**

![This is an image](https://github.com/Jahill17/Cryptocurrencies/blob/main/ScreenGrabs/Deliv3_ClusteredDF.png)


![This is an image](https://github.com/Jahill17/Cryptocurrencies/blob/main/ScreenGrabs/Deliv3_ElbowCurve.png)
- The above image is an elbow curve to find the best value for K.  The best value for K is 4 in this instance.


**The last deliverable required visualizing the cryptocurrencies results**

![This is an image](https://github.com/Jahill17/Cryptocurrencies/blob/main/ScreenGrabs/Deliv4_3DScatterClusters.png)
- The above image is a 3D-Scatter with the PCA data and the clusters

![This is an image](https://github.com/Jahill17/Cryptocurrencies/blob/main/ScreenGrabs/Deliv4_TradeableCryptos.png)
- The above image is a table of cryptocurrencies printed

![This is an image](https://github.com/Jahill17/Cryptocurrencies/blob/main/ScreenGrabs/Deliv4_HVplotScatter.png)
- The above is an hvplot scatter of the clustered dataframe


