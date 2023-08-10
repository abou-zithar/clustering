# Customer Segmentation using Clustering
This README file explains the Python code that performs customer segmentation using clustering techniques on customer data. The dataset used for this analysis is from the "Mall_Customers.csv" file.

## Dataset
The dataset contains customer information such as annual income and spending score.

## Code Overview
The code is divided into the following sections:

## Data Loading and Preprocessing
The code starts by importing necessary libraries and loading the dataset using pandas. It drops the "CustomerID" column and keeps only the relevant features for analysis.

## Clustering with K-Means
The code uses the K-Means algorithm to cluster the data points. It determines the optimal number of clusters using the elbow method and then fits the K-Means model with the chosen number of clusters. The predictions for each data point are obtained using model.predict().

## Data Visualization
The code visualizes the clustered data points using scatter plots. It plots each cluster with a distinct color and displays the cluster centers as yellow points.

## Hierarchical Clustering
The code then performs hierarchical clustering using the AgglomerativeClustering algorithm. It uses the dendrogram to visualize the hierarchy of clusters.

## Agglomerative Clustering Visualization
Finally, the code visualizes the data points clustered using the AgglomerativeClustering algorithm. Similar to K-Means, it uses scatter plots to display different clusters with different colors.

## Conclusion
This README provides an overview of the customer segmentation analysis using clustering techniques. By dividing customers into distinct segments, businesses can gain insights into their behaviors and preferences, helping them tailor marketing strategies and improve customer satisfaction. The code can be used as a starting point for more in-depth analyses and insights.
