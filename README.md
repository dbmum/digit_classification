# Overview

As a software engineer I am always striving to meet new goals and learn new things. I enjoy challenging myself to learn complex new topics that I find interesting. 
THis has lead me to new places, and ultimately to nueral networks and the project I have today.

This project uses machine learning methods, specifically a nueral network, to train a program to be able to correctly guess handwritten digit images. The program trains through 15 epochs on 60,000 images, then it tests on 10,000 images. My program displays some of the correct guesses with the statistics of each possible digit that it could be, some of the guesses that it got incorrect, and then the overall accuracy percentage. On average my program gets 95% accuracy after only 3 minutes of training.

I wrote this program after a history of being very interested in machine learning. I thought this would be a great starting point to be able to understand more into the complex algorithms of machine learning. I am always understanding more and more the applications of such algorithms and look to implement them more into my programs in the future.

[Software Demo Video](https://youtu.be/1Rc1RrGKK8k)

# Development Environment

Google colab

Python

Pytorch

# Nueral Network specifications

* MNIST Dataset
* layer sizes - [784, 128, 100, 10]
* Optimization method - stochastic gradient descent (SGD)
* normalization method - sigmoid function
* Learning rate - 0.03
* momentum - 0.9

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Nueral network explanation series](https://youtu.be/aircAruvnKk)
* [Pytorch digit classification tutorial](https://towardsdatascience.com/handwritten-digit-mnist-pytorch-977b5338e627)
* [Pytorch documentation](https://pytorch.org/docs/stable/index.html)

# Future Work

* Add functionality to run on a GPU rather than CPU using pytorch cuda methods
* Be able to import my own images or drawings for my network to classify
* write my own backpropogation code for optimization
