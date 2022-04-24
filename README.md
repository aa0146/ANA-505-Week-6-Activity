# ANA-505-Week-6-Activity
ANA 505 Week 6 Activity

# Accuracy: 
SVM accuracy: 97.33% <br/>
K Means accuracy: 88.67% <br/>
C50 accuracy: 93.3% <br/>

# SVM: 
The Support Vector Machine algorithm is used to train on the entire iris dataset. "ggpairs" library is used to visualize the data by plotting histograms and scatter plots for different species. A plot of the generated model is plotted to help understand the support vector visualization. Later, the predictions are obtained using the trained model and a confusion matrix is used to get the misclassification error and accuracy.

# K Means: 
The sepal and petal length and width are normalized before implementing the K-means clustering algorithm. The result obtained after training the data with the K-means algorithm model, gives the size (number of records in the clusters), centers of the clusters and the cluster vector showing where each record belongs in a cluster. Plot is used to visualize the distributions of the data points as per the clusters. A table is obtained showing the classification of the data as per clusters, which can be used to obtain the correctly classified and misclassified instances.

# C50 Algorithm: 
Before implementing the algorithm, the data is split into train and test datasets. The model is trained on the training data using the C50 Algorithm. Plot() is used to visual the trained model. The predictions are performed on the test data using the previously generated model. CrossTable() is used to get the misclassifications and correctly classified instances in a tabular format. It also provides the rate of correctly classified (accuracy).   


