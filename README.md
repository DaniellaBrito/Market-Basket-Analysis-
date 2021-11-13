# Market-Basket-Analysis-
Brief Market Basket Analysis using Clustering 


#### The steps followed for this project has been outlined by John Rollins, IBM

1. Business Understanding
2. Analytical Approach
3. Data requirements
4. Data collection
5. Data Understanding
6. Data Preparation

## Libraries Used
Numpy
Pandas
Matplotlib
Seaborn
Scikit learn

###  Project Pipeline Understanding - 

1. Business Understanding
Customer segmentation is the practice of dividing a company's customers into groups that reflect similarity among customers in each group. The goal of this project is to divide customers into groups based on common characteristics in order to maximize the value of each customer to the business.

2. Analytical Approach
Clustering of Customers based on similar characteristics is an Unsupervised Learning as for each observation we do not have any target variable. For this project I will use two Machine Learning models

I will use KMeans Clustering Algorithm which aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean
I will also use Hierarchical clustering which is an algorithm that groups similar objects into groups called clusters. The endpoint is a set of clusters, where each cluster is distinct from each other cluster, and the objects within each cluster are broadly similar to each other.

3. Data Requirement 
Data Requirements and Data Collection
We would require a dataset that gives us information regarding customers from a market.

For this project, the dataset has been provided to us on Kaggle.

4.Data Understanding 
here is a total of 200 observations with each having 5 variables.
The column of the dataset includes CustomerID, Gender, Age, Annual Income, Spending Score.
There are no missing values to work with so far 
There is one categorical variable - Gender {{ img:d1e5fd }}

5. Feature Engineering 
Dropped CustomerID (not useful as it is unique for each customer)
Created Dummy Variable for Gender

K Means Clustering

First, we determine the optimal number of clusters
Then we determine starting values for each cluster

Hierarchical clustering
The endpoint is a set of clusters, where each cluster is distinct from the other cluster, and the objects within each cluster are broadly similar to each other.

