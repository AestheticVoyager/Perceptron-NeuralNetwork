# Simplest Possible Neural Network (Perceptron)

![demo](./demo.gif)

Frank Rosenblatt invented Perceptron program, on an IBM 704 computer at Cornell Aeronautical Labratory in 1957.
He proposed a Perceptron learning rule based on the original MCP neuron. A Perceptron is an algorithm for supervised learning of binary classifiers. This algorithm enables neurons to learn and processes elements in the training set one at a time.
The original Perceptron was designed to take a number of binary inputs, and produce one binary output.
There are two types of Perceptrons: Single layer and Multilayer.
The Perceptron algorithm learns the weights for the input signals in order to draw a linear decision boundary.
This enables you to distinguish between the two linearly separable classes +1 and -1.

## Perceptron Learning Rule
Perceptron Learning Rule states that the algorithm would automatically learn the optimal weight coefficients. The input features are then multiplied with these weights to determine if a neuron fires or not.
The Perceptron receives multiple input signals, and if the sum of the input signals exceeds a certain threshold, it either outputs a signal or does not return an output. In the context of supervised learning and classification, this can then be used to predict the class of a sample.

## Quick Start Guide

```console
$ ./build.sh
$ ./main
```
