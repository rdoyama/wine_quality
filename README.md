## Wine Type

The goal of this project is to predict the type of a specific wine given its properties, such as: acidity, sugar, sulfur, density, pH, etc. To be able to do that, we will use the [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) availabe from the **UC Irvine Machine Learning Repository** to train a simple neural network.

The model consists of three fully connected layers: the input layer with size 11, a hidden layer of size 8 and the output layer of size 1. With this configuration, our model is capable of predicting the type of wine with more than 99% accuracy. We also implement a logistic regression algorithm from scratch and train it using k-fold validation.
