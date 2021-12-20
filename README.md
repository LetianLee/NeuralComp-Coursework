# Neural Computation Coursework

[<img src="https://raw.githubusercontent.com/pytorch/pytorch/master/docs/source/_static/img/pytorch-logo-dark.png" width="10%">](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)   

This is the source code for the **Neural Computation Coursework**. The module *Neural Computation* contains 2 coursework projects focussing on neural network.  


## Coursework 1: Backpropagation and Softmax
The goal of this coursework is to implement and train a feedforward neural network with a softmax layer to classify pictures of fashion items from the [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) data set.

To complete the coursework 1, we are allowed to use the Numpy and Matplolib in Python 3. However, we are not allowed to use any neural network library which provides autograd functionality, such as PyTorch or TensorFlow.

We implemented the **backpropagation algorithm** and **mini-batch gradient descent**. The main code is in file:  
[**NeuralComp-Coursework/cw1-2020-files/backprop-softmax.py**](https://github.com/LetianLee/NeuralComp-Coursework/blob/main/cw1-2020-files/backprop-softmax.py)


## Coursework 2: Semantic Segmentation of Magnetic Resonance (MR) Images
The aim of this coursework is to develop an automated methodology using Convolutional Neural Network (CNN) that is capable of segmenting a cardiovascular magnetic resonance (CMR) image into four regions: the background, the left ventricle (LV), the right ventricle (RV) and the myocardium (Myo).

We implemented **U-Net** for this task. The code and the report are in file:  
[**NeuralComp-Coursework/CW2/tutorial.ipynb**](https://github.com/LetianLee/NeuralComp-Coursework/blob/main/CW2/tutorial.ipynb)
