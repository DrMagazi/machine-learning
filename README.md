# Machine Learning kNN notebooks
![](ml.jpeg)

## Introduction
This is a project I made during my introduction to machine learning course. The aim was to learn some ML techniques, 
specifically those using knn. It was the moment I realised that "Machine Learning" and "Artificial Intelligence" is 
just a really cool name for math. 

In this repo you can find 3 Jupyter notebooks with some custom kNN implementation and usage. The datasets used for the
machine learning are, of course, also here.

Read below for a brief description of the notebooks.

## *handwritten_digit_knn_classifier*
Here the very well-known MNIST dataset (A collection of handwritten digit images) was used to train a model that can
guess what number you wrote on a piece of paper, whiteboard, etc... 

A very high-level summary of how this works is that the image of the input digit is processed and placed as a point
(based on the coloring of each pixel) in a ~900 dimensional graph which is the model that contains the points of all 
other digits. Depending on what the parameter "k" is selected as, your digit will be predicted to be the same as its 
k nearest neighbors, hence, kNN.

Unfortunately there is no interface for you to conveniently check some number you wrote down or found on the internet
using this model at the moment, but I wish to implement that later.

## *knn_regression* and *knn_classification*
These are a little less interesting as they were the practice leading up to the digit classifier. *knn_classifier*
was the practice leading up to the digit classifier and therefore, works in a similar way except with nonsensical data
and the *knn_regression* is another knn technique that provides a continuous output rather than a discrete one.
