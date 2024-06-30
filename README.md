It demonstrates how to implement a K-means clustering algorithm to group customers based on their purchase history, specifically their annual income and spending score. Steps to Implement K-means Clustering for Customer Segmentation

1. Import Libraries:
   - Import necessary libraries for data manipulation, clustering, scaling, and visualization.

2. Load the Dataset:
   - Load the customer dataset into a pandas DataFrame.

3. Select Features:
   - Choose the relevant features for clustering, such as `Annual Income (k$)` and `Spending Score (1-100)`.

4. Standardize the Features:
   - Standardize the selected features to ensure they are on the same scale.

5. Apply K-means Clustering:
   - Apply the K-means clustering algorithm to the standardized features.
   - Specify the number of clusters (`n_clusters`).

6. Assign Cluster Labels:
   - Add the cluster labels to the DataFrame to identify which cluster each customer belongs to.

7. Visualize the Clusters:
   - Create a scatter plot to visualize the clusters, using different colors for different clusters.
   - Label the axes and add a title to the plot.

8. Display Customer Clusters:
   - Print the customer IDs along with their assigned cluster labels to see the segmentation results.
