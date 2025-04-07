# neural_network
This is a neural network model. Data is from the Keras dataset fashion_mnist. Fashion MNist dataset is 70,000 images of  garments and footwear in 10 categories. Separated 60,000 images is used for the training of the model and 10,000 images are set aside for testing the accuracy of the model. The model has an input and an output layer fully connected.

This model uses the Tensorflow platform and Keras APIs. The model is built as an instance of the Keras Sequence model and Keras Dense layer to connect the input and output layers fully. The output layer returns an array of 10 probabilities of floating numbers from 0 to 1. Mostly, out of 10 probabilities, only one is close to one (1) while the other numbers are so small and near to zero. The  So, after the training, the model needs to see the 60,000 images. it saves the weights and biases that will be used once we run the prediction method.

The code is in Google Colab Notebook and is linked here in GitHub. In Google Colab we can run this small model fast with a GPU  or TPU runtime (for free in few hours) . You can run and test the code by clicking the Google Colab button ![image](https://github.com/user-attachments/assets/963229eb-1638-438d-a89d-6b4f9ae64af9)
on the uppermost part of the code. 


Predicting the image from test data (randomly selected from 10,000 images). Sample result.

![Image_Prediction_Result](https://github.com/user-attachments/assets/ea37beeb-e4e9-492c-aee8-9c4316f905bd)



