# Crop-Classification-Using-KNN-and-SVM

This data set was obtained from:

The goal of this assignment was to classify crops using our own implementations of the KNN and SVM algorithms.

There were several issues with this assignment. One, the data set was too large, and KNN algorithm has a time complexity of O(n*m).
We initially tried to split the data into a training set with 300,000 training samples and 20,000 test samples, but found that the algorithm
was taking too long to classify. We decided to change the test set to be considerably small so that the algorithm could run in a reasonable amount
of time. Even though the algorithm was extremely accurate (100% correctly classified samples!), it took too long to obtain the classification.
KNN is a very good algorithm if you are looking for accuracy, but it needs to be run on data sets relatively small (around a few hundred to a few thousand
data points).
