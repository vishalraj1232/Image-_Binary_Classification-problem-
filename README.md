# Image_Binary_Classification-problem-
Image classifier with deep learning (CNN and Keras)

Author: Vishal Raj(vj)
## Problem Formulation :
 In this Section we are implementing Convolution Neural Network(CNN) Classifier for Classifying "apple" and "not apple" images. 
 ## Requirements:
* Jupyter notebook
* Tensorflow 2.0 and above
* Python 3.6 and above
* Matplotlib
* Pandas
* Numpy
* Keras
* Open CV
* Pickle

## Model Architecture:
Input Data Shape: 64x64x3
* Layer 1:

Convolutional Layer 32 filter Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

* Layer 2:

Convolutional Layer 32 filter Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

* Layer 3:

Convolutional Layer 64 filter Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

* Classification:

Flatten

Dense Size: 64

Activation Function: ReLu

Dense Size: 2

Activation Function: Softmax

* Optimizer: Adam
* Loss: Binary Crossentropy
