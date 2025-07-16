# Data Preprocessing
• The dataset is loaded using the Pandas library. 
• Basic exploratory data analysis (EDA) is conducted to understand the 
dataset structure. 
• Missing values are checked and handled appropriately.
• Only the relevant features (Annual Income and Spending Score) are 
selected for clustering.
# Elbow Method for Optimal K
• The Elbow Method is used to determine the optimal number of clusters.
• We plot the Within-Cluster Sum of Squares (WCSS) for different cluster 
values.
• The point where WCSS starts to flatten is chosen as the optimal number of 
clusters
# Applying K-Means Algorithm
• The K-Means clustering algorithm is applied using the optimal cluster count. 
• Each customer is assigned to a cluster based on their income and spending 
behavior.
# Visualization 
• A scatter plot is created to visualize the customer groups with different colors.
• The centroids of clusters are plotted to indicate the cluster 
