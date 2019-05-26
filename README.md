# Handwritten-digit-recognization-using-KNN-classifier
The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image. It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting.

* To read about the MINST handwritten dataset go to [Minst dataset](http://yann.lecun.com/exdb/mnist/)
* The data is already downloaded into two folder's named : 
    1. Training data<br>
        1.1 train-images.idx3-ubyte - It contains training data of 60,000 handwritten images.<br>
        1.2 train-labels.idx1-ubyte - It contains the label of the digit corresponding to the features.
    2. Test data<br>
        2.1 t10k-images.idx3-ubyte - It contains testing data of 10,000 handwritten images.<br>
        2.2 t10k-labels.idx1-ubyte - It contains the label of the digit corresponding to the features of test data.

# K-Nearest Neighbors
In pattern recognition, the k-nearest neighbors algorithm (k-NN) is a non-parametric method used for classification and regression.[1] In both cases, the input consists of the k closest training examples in the feature space. The output depends on whether k-NN is used for classification or regression:

In k-NN classification, the output is a class membership. An object is classified by a plurality vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1, then the object is simply assigned to the class of that single nearest neighbor.
In k-NN regression, the output is the property value for the object. This value is the average of the values of k nearest neighbors.
