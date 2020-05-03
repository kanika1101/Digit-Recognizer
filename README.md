# MNIST_PCA_SVM
A classifier to predict the label of a given digit using PCA and SVM

This kernel aims at building a classifier to predict the label of a handwritten digits using PCA and SVM

<b>Dataset</b>

The dataset consists of images of handwritten numeric digits between 0-9. Each image is of 28 x 28 pixels, i.e. 28 pixels along both length and breadth of the image. Each pixel is an attribute with a numeric value (representing the intensity of the pixel), and thus, there are 784 attributes in the dataset.

It can be found at the kaggle link
https://www.kaggle.com/c/digit-recognizer/data

<b>Problem Statement</b>

The task is to build a classifier that predicts the label of an image (a digit between 0-9) given the features. Thus, this is a 10-class classification problem.
Since this dataset has a large number of features (784), we will use PCA to reduce the dimensionality, and then, build a model on the low-dimensional data.

<b>Solution Overview:</b>

The following topics are covered in this tutorial

<b>Understanding and Exploring the Data
 
Dimensionality Reduction: </b>
PCA will be used to reduce the dimensionality of the dataset.

<b>Model building using SVM on PCA transformed data</b>
Linear, Poly and rbf kernel will be used to build the model and the comparisons will be done.

<b>Hyperparameter tuning and pipelining:</b>
Final model will be built with the help of hyperparameter tuning by cross validation grid search and pipeline functionality.
