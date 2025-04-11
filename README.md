# Neural Network 

---

## 1. INTRODUCTION

This is a neural network model and it is a supervised machine learning model. Data is from the Keras dataset fashion_mnist. Fashion MNist dataset is 70,000 images of  garments and footwear in 10 categories. The 70,000 images are labeled with numbers from 0 to 9 (0 if "Ankle Boot", 1 if "Trouser", 2 if "Pullover", etc). Separated 60,000 images are used for the training of the model and 10,000 images are set aside for testing the accuracy of the model. The model has an input and an output layer fully connected.

---

## 2. RESOURCES

This model uses the Tensorflow platform and Keras APIs. The model is built as an instance of the Keras Sequence model and Keras Dense layers. The Dense layer is designed to connect the input and output layers fully. The output layer returns an array of 10 probabilities of floating numbers from 0 to 1. Mostly, out of 10 probabilities, only one is close to one (1) while the other numbers are so small and near zero. So during the  the training, the model will see the 60,000 images. it saves the weights and biases that will be used once we run the prediction method.

The code is in Python in the Google Colab Notebook environment. This is cloud-based training using Nvidia Turing T4 GPU with 15 GB RAM, 16GB CPU, and 100 GB memory.

You can run and test the code by clicking the Google Colab button that looks like this ![image](https://github.com/user-attachments/assets/963229eb-1638-438d-a89d-6b4f9ae64af9)
on the uppermost part of the code. 

---

## 3. TRAINING OBJECTIVES

  - To achieve 96% accuracy
  - To determine how many iterations or epochs to reach this accuracy level
  - To determine how long it would take to train the model to reach this level of accuracy
      Note: We will use a T4 (Turing) Nvidia GPU with 15 GB RAM, and a CPU with 16 GB RAM
  - To know the evaluation accuracy using the test dataset (of 10,000 images)

---

## 4. TRAINING RESULTS

  - The 96% accuracy was achieved at the 44th epoch. It took 218 seconds to complete the training.


       ![Model Training Result](https://github.com/user-attachments/assets/f4c52702-2701-4422-b8cc-84e92755158c)



## 5. MAKING PREDICTIONS

  Predicting the image from test data (randomly selected from 10,000 images). Sample result.


  ![Image_Prediction_Result](https://github.com/user-attachments/assets/ea37beeb-e4e9-492c-aee8-9c4316f905bd)




