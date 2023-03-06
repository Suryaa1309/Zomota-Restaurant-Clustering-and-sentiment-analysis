# Zomota Restaurant Clustering and Sentiment Analysis

## Introduction
Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities.
     India is quite famous for its diverse multi cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity. Restaurant business in India is always evolving. More Indians are warming up to the idea of eating restaurant food whether by dining outside or getting food delivered. The growing number of restaurants in every state of India has been a motivation to inspect the data to get some insights, interesting facts and figures about the Indian food industry in each city. So, this project focuses on analysing the Zomato restaurant data for each city in India

## Problem Statement 
The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and made some useful conclusion in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is vizualized as it becomes easy to analyse data at instant. The Analysis also solve some of the business cases that can directly help the customers finding the Best restaurant in their locality and for the company to grow up and work on the fields they are currently lagging in.
This could help in clustering the restaurants into segments. Also data has valuable information around cuisine and costing which can  be used in cost vs. benefit analysis Data could be used for sentiment analysis. Also the metadata of reviewers can be used for identifying the critics in the industry.

## Steps Involved 
### Exploratory Data Analysis 
After loading the dataset we performed this method. This process helped us figuring out various aspects and relationships among the target and the independent variables. It gave us a better idea of which feature behaves in which manner compared to the target variable.

### Null values Treatment
Our dataset contains a large number of null values which might tend to disturb our accuracy hence we dropped them at the beginning of our project inorder to get a better result.
### Standardization of features
Our main motive through this step was to scale our data into a uniform format that would allow us to utilize the data in a better way while performing fitting and applying different algorithms to it. 
The basic goal was to enforce a level of consistency or uniformity to certain practices or operations within the selected environment.
### Fitting different models
For modelling we tried various classification algorithms like:
### Support Vector Machine 
### Random Forest Classifier
### XGB

### Support Vector Machine 
 SVM is used mostly when the data cannot be linearly separated by logistic   regression and the data has noise. This can be done by separating the data with a hyperplane at a higher order dimension.

### Random Forest Classifier:
Random Forest is a bagging type of Decision Tree Algorithm that creates a number of decision trees from a randomly selected subset of the training set, collects the labels from these subsets and then averages the final prediction depending on the most number of times a label has been predicted out of all.

### XG Boost
XGBoost is one of the fastest implementations of gradient boosting. trees. It does this by tackling one of the major inefficiencies of gradient boosted trees: considering the potential loss for all possible splits to create a new branch (especially if you consider the case where there are thousands of features, and therefore thousands of possible splits). XGBoost tackles this inefficiency by looking at the distribution of features across all data points in a leaf and using this information to reduce the search space of possible feature splits.

## Clustering 
### K-Means Clustering 
### PCA Principle Components Analysis 

### K-Means Clustering 
K-Means Clustering is an unsupervised learning algorithm that is used to solve the clustering problems in machine learning or data science. The K-means clustering algorithm computes centroids and repeats until the optimal centroid is found. It is presumptively known how many clusters there are. It is also known as the flat clustering algorithm. The number of clusters found from data by the method is denoted by the letter ‘K’ in K-means.

### Principle Components Analysis 
Principal Component Analysis (PCA) is a statistical procedure that uses an orthogonal transformation that converts a set of correlated variables to a set of uncorrelated variables. PCA is the most widely used tool in exploratory data analysis and in machine learning for predictive models. Moreover, PCA is an unsupervised statistical technique used to examine the interrelations among a set of variance

### Conclusion 
The most popular cuisines are the cuisines which most of the restaurants are willing to provide. The most popular cuisines in Hyderabad are North Indian, Chinese, Continental, and Hyderabadi. Sentiment Analysis was done on the reviews and a model was trained in order to identify negative and positive sentiments. 
SVM and XGB both performed well and we can choose any one them,SVM and XGB are having 0.921 and 0.981 of testing accuracy respectively.
 We got best cluster as 5 in K-Means and Principal Component Analysis(PCA).

