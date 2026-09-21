# Handwriting Recognition Using NN

This neural network model is built in Python using the NumPy library to accurately classify handwritten digits from the MNIST dataset.

* The MNIST Data is loaded and reshaped (vectorized) into arrays.
* It is preprocessed by normalizing the image data and one-hot encoding the image labels.

* The model is trained and tested on identifying handwritten digits from the MNIST dataset.
* Only 1 Hidden layer is used in this model to pass inputs forward and propagate the gradient derivatives of a loss function backward.
* ReLU activation function is applied to hidden layer outputs.
* Dropout is used for regularization.
* The loss function used is a basic Mean Squared Error

* The model is optimized by first adding the Softmax function to the output layer.
