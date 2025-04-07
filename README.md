# neural_network
My first neural network model. Data is from Keras dataset fashion_mnist. Fashion MNist dataset is 70,000 images of  garments and footwear in 10 categories. Separated 60,000 images is used for the training of the model and 10,000 images is set aside for testing the accuracy of the model. The model has an input and an output layer fully connected.

This model uses Tensorflow platform and Keras APIs. The model is built as an instance of keras Sequence model and keras Dense layer to fully connect the input and output layer. The output layer returns an array of 10 probabilities of floating numbers from 0 to 1. So, after the training by which the model need to see the 60,000 pieces of images. it saves the weights and biases that will be used once we run the predict method.
