# Image Classification

In this project, I created a Machine Learning project using a CNN (Convolutional Neural Network) model to classify images of a hand and predict whether the hand is in the form of rock, scissors, or paper. This project using the TensorFlow framework and the CNN model.

The purpose of this project is to create a model that can classify images into 3, that is images of hands in the form of stones, scissors, paper.

The dataset used for this project is a collection of data in the form of images that have a png format which is an image of a hand that has the shape of stone, scissors, and paper. This dataset has a total of 2188 images, of which 712 are paper-shaped, 726 are rock-shaped, and 750 are scissors-shaped. The Source of this dataset is [here]( https://dicodingacade-my.blob.core.windows.net/picodiploma/ml_pemula_academy/rockpaperscissors.zip).

The steps taken in this project are:
1.	Extract the zip file from the drive with the unzip method.
2.	Divide the data into 3 parts, that is train data, validation data, and test data.
3.	Move the test data directory to the drive, so that the test data can be tested after the model is finished.
4.	Perform pre-processing for train data and validation data with image augmentation.
5.	Building a CNN model architecture. Build a CNN model architecture. This CNN architecture uses 2 layers of convolution layer and max-pooling layer, and then the data is entered into 2 hidden layers with 2 dropout layers. The output layer has 3 outputs. The activation function used for all layers is ReLU, while the activation function for the output layer is softmax.

6.	Compile the model with model.compile, using the loss function: categorical_cressentropy and the optimizer: Adam algorithm.
7.	Train the model with model.fit by repeating 5 times (epoch = 5).
8.	Calculating test loss and accuracy tests
9.	Make image predictions using test data to test whether the model is accurate or not.

This code can run on Google Colaboratory [here](https://drive.google.com/drive/folders/1m_m9NDipJ1yzMZAW8yEAwH0TDF8HFZNl?usp=sharing).

For the results of image classification, and portfolio for this project in pdf can be accessed [here](https://drive.google.com/file/d/1Uw3DYYBzA6dc1tTyoTfIC06rQ3gQwgUi/view?usp=sharing).



