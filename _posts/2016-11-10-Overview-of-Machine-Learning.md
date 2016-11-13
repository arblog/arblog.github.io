---
layout: post
title: Quick Overview of Machine Learning
date: 2016-11-10
post_author: Achyut Reddy
---
So what exactly is machine learning? At the very basic level, machine learning aims to predict an output from a input. 
The novelty of machine learning is that it learns to do this without being explicitly told how to by a programmer. 

Machine learning is a very broad term and is split up into two main categories, supervised and unsupervised learning. 

## Supervised Learning
Supervised learning is used when you have a labeled data set. 
The algorithm must then predict the output for new inputs based on the known data set.
The two most common types of supervised learning are regression and classification.

### Regression
The goal for regression algorithms, is to output a continuous value based on an input.
There is usually a cost or error function, that the algorithm tries to minimize.
The most well known form of this is linear regression.

### Classification
Classification is very similar to regression in that it also tries to minimize a certain cost function, but the difference is that instead of predicting a continuous output, 
it categorizes the object into a class based on training data whose classes are already known. 
An example would be identifying the contents of an image.

### Reinforcement Learning
This is a bit different to the previous two types of learning. The most different part of reinforcement learning is the method for training these algorithms. 
Instead of minimizing a cost function, you maximize your reward. 
The reward is something that the programmer sets for a desired value. 
For example, if you are training the algorithm to play a game, you can increase the reward every time the algorithms gets a point, and decrease the reward every time it loses a point.

## Unsupervised Learning
Unsupervised learning is useful when you are given a data set, but don't know the true labels for the data. 
The goal for unsupervised learning is to find structure in the data. 
An example would be to try to identify fraudulent credit card activity, if you were to use classification for this problem, you would need a very large data set containing equal amounts of fraudulent and normal credit card transactions.
This is obviously not ideal because it would be hard to create this data set, and you also don't want to wait until you have enough credit card fraud, you want to identify it immediately.

## What Can Machine Learning Do?
Machine Learning can do a lot of tasks that are very hard to program manually. For example, handwriting recognition.
One of the first implementations of this was by Yann LeCun with LeNet. You can see some demos of this in action [here](http://yann.lecun.com/exdb/lenet/index.html).

More recently, Google's DeepMind beat the world's best Go player. Go has been very hard for AI to play because of the sheer amount of possibilities in a game.
You can see the games are read more about this on [DeepMind's Website](https://deepmind.com/research/alphago/).
