# Building-deep-neural-network-from-scratch
Building a deep neural network writing all the subroutines without using any ML library or any deep learning framework and applying it to the task of image classifiaction of 'cat' or 'no cat'.
We will first build network for two layers and then generalizing it to user input layers and user input neurons in each layers.
We define two activation function named ReLu and sigmoid, it is proved from experiment that 'ReLu' is best suited for hidden layers and 'sigmoid' is best suited for output layer.
If we initilaize the weights with zero it may lead to low changes in cost function, hence weights are randomly initialized.
We first make .ipynb file for basic subroutines and then we will craete dnn_app_utils_v3.py file with those subroutines which would be called for our application from.
