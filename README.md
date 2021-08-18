# Cryptocurrencies


The purpose of this project was to use unsupervised machine learning. Specifically in relation to Cryptocurrencies. Unsupervised machine learning is used to help group data into clusters.

Deliverable 1:
For the first part, we prepared the data for analysis. This included removing cryptocurrency that is not being traded. Removing unused columns and rows with null values. Converting data types, using get dummies to convert strings to numeric values. And finally scaling the data.

Deliverable 2:
The next part in preparing the data was reducing dimension using PCA. We created 3 principal components.

Deliverable 3:
Next we used K means to cluster the data. First we created an Elbow chart to determine the ideal number of clusters. Based on the Elbow chart, we decided we wanted to create 4 clusters. So, the data was divided into 4 classes using K means.

Deliverable 4:
Finally, we visualized our clusters. We created a 3-D graphy using plotly express to create a 3-D chart. We used the 3 PCA components for the X, Y, and Z axis and the classes to color code the chart. Next we used the min max scaler method instead of the standard scaler method, and created a 2-D scatter plot.