# Clustering

This is a project that uses customer data to segment the customer base.  The data consists of Gender, Age, Annual Income, and a score (1-100), created by the mall on the customer's spending behavior based on prior purchasing history. 

The goal is to segment the customer base into different groups based on the annual income and the spending score.  

Since we will first use k-means we first need to identify the optimal number of clusters.  Using the "elbow method" we find the optimal number of clusters and then run the k-means algorithm to segment the customers. 

# Heirarchial Clustering

The second goal is to tackle the customer segmentation problem based on heirarchial clustering.  Similar to k-means, we will not assume to know the number of clusters.  We use a dendrogram to find the optimal number of clusters.  Once the optimal number of clusters are obtained we fit heirarchial clustering to the mall dataset. 
