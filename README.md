# neural_network
This is a neural network model. Data is from the Keras dataset fashion_mnist. Fashion MNist dataset is 70,000 images of  garments and footwear in 10 categories. Separated 60,000 images is used for the training of the model and 10,000 images are set aside for testing the accuracy of the model. The model has an input and an output layer fully connected.

This model uses the Tensorflow platform and Keras APIs. The model is built as an instance of the Keras Sequence model and Keras Dense layer to connect the input and output layers fully. The output layer returns an array of 10 probabilities of floating numbers from 0 to 1. So, after the training, the model needs to see the 60,000 images. it saves the weights and biases that will be used once we run the prediction method.

The code is in Google Colab Notebook and is linked here in GitHub. You can run and test the code by clicking the Google Colab button on the uppermost part of the code. 
