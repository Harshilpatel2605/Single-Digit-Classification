# Single Digit Classification using Bernoulli Naive Bayes

This project implements a Bernoulli Naive Bayes classifier for handwritten digit recognition using the MNIST dataset. It also allows users to test their own 28x28 images of digits.
Features

    Trains on MNIST Dataset: Uses fetch_openml to load and preprocess MNIST data.

    Bernoulli Naive Bayes Model: Implements a probabilistic classifier for digit recognition.

    Custom Image Input: Allows users to input their own 28x28 images of handwritten digits for classification.

    Binarization & Preprocessing: Converts grayscale images to binary format for better classification.

## Input

The input image should be 28x28 pixels, and must have white digits written on black background(similar to that in MNIST dataset).

## Output

The model will output:

    The Original colored Image & The preprocessed image visualization.

    Predicted digit with its probability distribution.

Example

Predicted Digit: 8 with probability: 0.99
