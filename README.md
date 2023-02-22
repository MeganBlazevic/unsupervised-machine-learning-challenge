# Unsupervised-Machine-Learning-Challenge

The goal of this Module 20 challenge is to predict myopia. The research team that I work for belive that we may be able to take a specific group of patients and draw conclusions; that dont' present for the entire data population. So using unsupervised learning; fit the data into machine learning modules to explore the data.  Then create some visualizations to share our findings with our business stakeholders. 

## Programs Used
- Pandas
- SkLearn (KNeighbors; Standard Scaler, PCA, TNSE, KMEANS)

## Prepare the Data
Import the myopia csv file that was given to us.  We were asked to put that into a pandas data frame. As this is a large data set removing the myopic (which is used for the machine learning) is key to remove any biases in the data. Standardizing the dataset was also needed. 

## Apply Dimensionality Reduction
Perform dimesinality reduction with PCA.  

How did the number of features change?
I rand tests of 80%, 90%, 99%.  As the hint suggested in the challenge outline, we were to utilize 90%.

Run a t-SNE test to inspect the results.  Creating a scatter plan of the output to learn if there are distinct clusters.

## Perform a Cluster Analysis with K-Means
Create an elbow plot to identify the appopriate number of clusters. 

Looks like there are 10 different components; and according to the elbow curve; there should be 3 clusters.

## Make a Recommendation
**Can the patients be clustered? If so, how many clusters.**

After preparing all of the data, applying the dimensionality reduction utilizing our PCA method, futher focusing the data by using a t-SNE method; a cluster analysis was complete.  When doing unsupervised learning on the Myopia data; 3 is the optimal cluster count for our data set with a sample size of 618. 

When looking at the 3 scatter plots that were created; I don't believe that the t-SNE analysis providing additioanl information; as it appeared that there were 5ish clusters. This could be due to the random noise; or adjustments in the data. 