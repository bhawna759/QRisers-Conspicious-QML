# MNIST-Deep-Learning 
get hands dirty with the famous digit recognition problem using the MNIST (Mixed National Institute of Standards and Technology) database

The MNIST database contains binary images of handwritten digits commonly used to train image processing systems. The digits were collected from among Census Bureau employees and high school students. The database contains 60,000 training digits and 10,000 testing digits, all of which have been size-normalized and centered in a fixed-size image of 28 × 28 pixels. 

To get warmed up to the MNIST data set run python main.py. This file provides code that reads the data from mnist.pkl.gz by calling the function get_MNIST_data that is provided for you in utils.py. The call to get_MNIST_data returns Numpy arrays:

train_x : A matrix of the training data. Each row of train_x contains the features of one image, which are simply the raw pixel values flattened out into a vector of length . The pixel values are float values between 0 and 1 (0 stands for black, 1 for white, and various shades of gray in-between).

train_y : The labels for each training datapoint, also known as the digit shown in the corresponding image (a number between 0-9).
test_x : A matrix of the test data, formatted like train_x.

test_y : The labels for the test data, which should only be used to evaluate the accuracy of different classifiers in your report.
Next, we call the function plot_images to display the first 20 images of the training set. Look at these images and get a feel for the data


1. Experimented with Convolution, Pooling, ImageGenerator using Tensorflow on MNIST dataset
   (MNIST Classification using Tensorflow.ipynb)
2. MNIST Classification using Pytorch
3. MNIST code using JAX

   Bhawna's Task - understand and run codes for MNIST NN code using pytorch, MNIST code using JAX by 8th July
, MNIST using QNN by 10th July

