# Cryptocurrencies
**Using Unsupervised Machine Learning to examine the outcome of Cryptocurrencies data and how to analyze it.** 

## Analysis Overview

**The purpose of this project is to use Unsupervised Machine Learning to analzye a cryptocurrencies database and create a report that includes traded cryptocurrencies classified by their Unsupervised Machine Learning groups and feaures. This classification report can be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients. 
We use the following methods for the analysis:**

- **Preprocessing the Data for PCA**
- **Reducing Data Dimensions Using PCA**
- **Clustering Cryptocurrencies Using K-means**
- **Visualizing Cryptocurrencies Results**



## **Resources**
***Data Source:******[Crypto Data](https://min-api.cryptocompare.com/data/all/coinlist)***

***Software: Python 3.8.8, Anconda Navigator 2.1. 1, Conda 4.11.0, Jupyter notebook 6.4.6***


## **Results**

**After preprocessing and filtering the cryptocurrency data there are a total 532 tradable cryptocurrencies.**

### **Clusterig Cryptocurrencies using K-means - "Elbow Curve"**

**Using Unsupervised Machine Learning there is no known output. To group the cryptocurrencies, I will be using clustering algorithms alao known as the K-Mwan and project the findings using  data visualizations.** 
**Using the K-Means method the results produced the Elbow-Curve, which iterates k-values from 1-10**

<img src= "img/Elbow Curve.png" >

**The best k-value appears at the Elbow-Curve of 4 and as a result an output of 4 clusters can categorize the cryptocurrencies data.**

### **Visualizing Crypocurrencies Results**

### **3D-Scatter plot with Clusters**

<img src= "img/HV.Scatter & Clusters 1.png" >
<img src= "img/HV.Scatter & Clusters 3.png" >

**These 3D Scatter Plots were obtained using the PCA Algorithim to reduce the cryptocurrencies dimensions to three principal components** 

### **2D Scatter plot with clusters** 

<img src="img/HVplot Scatter .png" >
<img src="img/HV Scatter Plot 2.png" >

**These 2D-HV Scatter plot's above were obtained using the PCA algorithm to reduce the cryptocurrency data using TotalCoinsMined and TotalCoinsSupply in the X & Y axis. The cyrptocurrency BitTorrent coin in Class #2 is the unique outlier in this HV Scatter plot.** 

### **Tradable Cryptocurrencies Table**

<img src="img/Tradable Cryptocurrencies Table .png" >

**According to the Tradable Cryptocurrency Table most of the cryptocurrency coins are from classes 0 and 1. The highlighted BitTorrent coin is the only cyrptocurrency coin in class 2.**

## **Summary**

**In summary various steps such as preprocessing the data, reducing the data dimensions, using the K-means to cluster the cryptocurrencies and finally visualize the cryptocurrencies data were used to help classify the output data in the Unsupervised Machine Learning process.  As a result, the data has identified the classification of 532 cryptocurrencies based on similarities of their features. This ultimately gives a wide range of investment opportunities for clients to use to diversify their portfolio investments.**

