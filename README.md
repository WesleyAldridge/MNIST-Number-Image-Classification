# MNIST Number Image Classification

![Image by Josef Steppan on Wikipedia](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

## In this notebook:
-- Used logistic regression with mean squared error loss and mini-batch stochastic gradient descent to train 10 classifiers to predict the label of numeric images as a number between 0 and 9.

-- Trained 10 classifiers that perform binary classification: Is the input image the digit i or is it a digit different from i? Each of the ten classifiers has an input layer consisting of 28 x 28 input neurons and an output layer consisting of a single output neuron. Here, the 28x28 input neurons represent the 28x28 pixels of the input images, and the single output neuron represents the binary classification for each classifier.

-- Implemented mini-batch stochastic gradient descent manually using only numpy (i.e. without the use of Tensorflow/Keras).

-- Used argmax to determine the classifier with the strongest output and declared the corresponding digit as output.
