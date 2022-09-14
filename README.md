# Module-18-Challenge Cryptocurrencies - Unsupervised learning
# Overview of Project #
The purpose of this Project is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment, so that they can help the customers by offering a new cryptocurrency investment portfolio.The data need to be processed to fit the machine learning models by using unsupervised learning.To group the cryptocurrencies,clustering algorithm is used.

The analysis consisted of the following:
1. Preprocessing the Data for PCA.
2. Reducing Data Dimensions Using PCA.
3. Clustering Cryptocurrencies Using K-means.
4. Visualizing Cryptocurrencies Results.

# Resources #
Software: Jupyter Notebook <br>
Libraries: numpy, pandas, matplotlib, plotly, scikit-learn,hvplot,<br>
Data Sources: crypto_data.csv

# Results #
## Credit Risk Resampling Techniques ##
### Naive Random Oversampling ###
- Balanced Accuracy: 0.65%
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall High Risk: 62%
- Recall Low Risk: 68% <br>

![Naive Random Oversampling](/Image/Naive_Random_Oversampling.png)

### SMOTE Oversampling ###
- Balanced Accuracy: 0.62%
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall High Risk: 59%
- Recall Low Risk: 66% <br>

![SMOTE_Oversampling](/Image/SMOTE_Oversampling.png)

### Undersampling ###
- Balanced Accuracy: 0.51.6%
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall High Risk: 60%
- Recall Low Risk: 43% <br>

![Undersampling](/Image/Undersampling.png)
## SMOTEENN Algorithm to Predict Credit Risk ##
### Combination (Over and Under) Sampling ###
- Balanced Accuracy: 0.64.6%
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall High Risk: 71%
- Recall Low Risk: 58% <br>

![Combination (Over and Under) Sampling](/Image/Combination_(Over_and_Under)_Sampling.png)

## Ensemble Classifiers to Predict Credit Risk ##
### Balanced Random Forest Classifier ###
- Balanced Accuracy: 0.78.7%
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall High Risk: 67%
- Recall Low Risk: 91% <br>

![Naive Random Oversampling](/Image/Balanced_Random_Forest_Classifier.png)

### Easy Ensemble AdaBoost Classifier ###
- Balanced Accuracy: 0.92.5%
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall High Risk: 91%
- Recall Low Risk: 94% <br>

![Easy_Ensemble_AdaBoost_Classifier](/Image/Easy_Ensemble_AdaBoost_Classifier.png)
