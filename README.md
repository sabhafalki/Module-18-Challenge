# Module-18-Challenge Cryptocurrencies - Unsupervised learning
# Overview of Project #
The purpose of this Project is to create a report that includes which cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment, so that they can help the customers by offering a new cryptocurrency investment portfolio.The data need to be processed to fit the machine learning models by using unsupervised learning.To group the cryptocurrencies,clustering algorithm is used.

The analysis consisted of the following:
1. Preprocessing the Data for PCA.
2. Reducing Data Dimensions Using PCA.
3. Clustering Cryptocurrencies Using K-means.
4. Visualizing Cryptocurrencies Results.

# Resources #
Software: Jupyter Notebook <br>
Libraries: numpy, pandas, plotly, scikit-learn,hvplot,<br>
Data Sources: crypto_data.csv

# Results #
### Preprocessing the Data for PCAs ###
- The **crypto_df** DataFrame, We perfrom certain steps to preprocessing the data. After that, Standardize the data with StandardScaler() to removing the mean and scaling to unit variance.<br>

![Naive Random Oversampling](/Image/Naive_Random_Oversampling.png)
![Naive Random Oversampling](/Image/Naive_Random_Oversampling.png)
### Reducing Data Dimensions Using PCA ###
- PCA is a statistical technique to speed up machine learning algorithms when the number of input features (or dimensions) is too high. PCA reduces the number of dimensions by transforming a large set of variables into a smaller one that contains most of the information in the original large set.<br>

![SMOTE_Oversampling](/Image/SMOTE_Oversampling.png)

### Clustering Cryptocurrencies Using K-means ###
- K-means is an unsupervised learning algorithm used to identify and solve clustering issues. Done creating a new **clustered_df** DataFrame.
- Elbow curve is used etermine optimal value of k.we conclude that the optimal number of clusters for the data is 4.<br>

![Undersampling](/Image/Undersampling.png)

### Visualizing Cryptocurrencies Results ###
- scatter_3d plots represents individual data in three-dimensional space.
- hvplot.scatter plot used to improve consistency or to provide additional functionality.

![Combination (Over and Under) Sampling](/Image/Combination_(Over_and_Under)_Sampling.png)

