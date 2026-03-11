# An Introduction to Convolutional Neural Networks

Tags: #pattern-recognition #artificial-neural-networks #ann #convolutional-neural-networks #cnn #machine-learning #image-analysis

## Paper
Keiron O’Shea & Ryan Nash (2015).  
An Introduction to Convolutional Neural Networks.  

## Purpose
This paper provides an introduction to CNNs.

## Introcuction
**Artificial Neural Network (ANN)**
A computational processing system that is inspired by how the biological nervous system (human brain) works. One of the largest limitations of traditional forms of ANN is that they tend to struggle with the computational complexity required to compute image data. They can manage benchmarking datasets such as the black and white MNIST database of handwritten digits.

**Convolutional Neural Network (CNN)**
A form of ANN that is primarily used to solve difficult image-driven pattern recognition tasks.

## Learning Paradigms
There are two key learning paradigms in image processing tasks:

1. Supervised Learning
Learning through pre-labelled inputs to reduce the model's overall classification error.
  
2. Unsupervised Learning
The training set does not include any labels. Success is usually determined by whether the network is able to reduce or increase an associated cost function.

## Overfitting
Increasing the number of hidden layers and the number of neurons in an ANN could lead to two problems. The first is the need for more computational power and time to train these huge ANNs, which could become impractical. The second is a phenomenon called **overfitting**, which is basically when a network is unable to learn effectively due to a number of reasons. The less parameters required to train, the less likely the network will overfit- and of course, improve the predictive performance of the model.

## CNN Architecture

