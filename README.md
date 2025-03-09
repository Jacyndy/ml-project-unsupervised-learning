# machine_learning_project-unsupervised-learning

## Project Outcomes
- Unsupervised Learning: perform unsupervised learning techniques on a wholesale data dataset. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.
### Duration:
Approximately 1 hour and 40 minutes
### Project Description:
In this project, I will applied unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Unsupervised learning: We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine the optimal number of clusters and communicate the insights gained through data visualization.

The ultimate goal of the project is to gain insights from the data sets on customer segementation and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

# Findings
* From the results, we see that there is a srtong relationship between milk and detergent paper, aw weell as between grocery and detergent paper
* The data is mostly skewed to the right, hence we used MinMaxScaler.
* We reduced our fearures to 2 using PCA but these didn't improve our data as can be seen with the explaned variance ratio.
* Using the elbow rule to determine K, the optimal K is 4.
* Using scaled data before applying PCA, the KMeans resukts showed the following:
    * Cluster 0 shows client that buy more milk, grocery and deterent paper
    * Cluster 1 shows clients that buy more of fresh, and less of others.
    * In cluster 2 we see that we have clients that buy a lot of detergents paper, milk and grocery. 
    * Cluster 3 shows client that buy more of every products.
* The optimal number of clusters for hierichal clustering is 3.

