# Image-Classification
CS909-Image Classification


In this assignment, the objective is to develop object classification solutions using classical machine learning methods.
Specifically, we shall be solving an object recognition task. Each object is represented by a 28x28
dimensional image in a single 'flattened' 784 dimensional vector with an associated label (+1 or -1).


Dataset:

Xtrain: Training Data (each row is a single image)

Ytrain: Training labels

Xtest: Test labels (each row is a single image)


Task:

You will use Xtrain and Ytrain for training, validation and model selection. The project gives solutions to five questions including:

Q1.
Showing the data

Q2.
Performing 5-fold stratified cross-validation over the training dataset using the k = 1 nearest neighbour classifier

Q3.
Use 5-fold stratified cross-validation over training data to choose an optimal classifier between: k-nearest neighbour, Perceptron, Naïve Bayes Classifier, Logistic regression, Linear SVM and Kernelized SVM.

Q4.
Applying PCA to reduce the number of dimensions of the data.

Q5.
Develop an optimal pipeline for classification based on the analysis (Q1-Q4).
