# Handwritten-Digit-Recognition-Internship
This project was performed as part of an internship at BISAG-N or Bhaskaracharya National Institute for Space Applications and Geo-informatics, in a group of four members and a mentor. Working collaboratively allowed us to leverage each team member's strengths and knowledge, ensuring that we achieved the best possible results.
In this project we have understood the process of building a simple yet powerful Convolutional Neural Network (CNN) to recognize handwritten digits using TensorFlow and Keras. 
Handwritten digit recognition is one of the classic problems in the field of computer vision. The MNIST dataset is a standard dataset used for training and testing machine learning algorithms, especially neural networks.

# Dataset Description
The MNIST (Modified National Institute of Standards and Technology) dataset is a large database of handwritten digits commonly used for training and testing various image processing systems. It is a classic benchmark dataset in the field of machine learning and computer vision.

Data Composition:
Training Set: 60,000 images
Test Set: 10,000 images

Image Details:
Resolution: 28x28 pixels
Color Channels: 1 (grayscale)
Pixel Intensity: Ranges from 0 (black) to 255 (white)

Labels:
Each image is labeled with a digit from 0 to 9.
There are 10 classes corresponding to the digits 0 through 9.

# Project Description
# Importing Libraries
First, we'll import the necessary libraries. We'll be using numpy for numerical operations, tensorflow and keras for building and training our neural network, matplotlib for visualizations, and cv2 for image processing.

# Data Preparation
In the data preparation phase for the MNIST handwritten digit recognition project, the dataset is first loaded, consisting of 60,000 training images and 10,000 test images, each with dimensions of 28x28 pixels. The grayscale images are reshaped to include a color channel dimension, resulting in a 3D array format (28, 28, 1). To standardize the input and improve model performance, pixel values are normalized to a range of 0 to 1 by dividing by 255. Additionally, the categorical labels, representing digits from 0 to 9, are converted into one-hot encoded vectors to facilitate classification tasks. This structured and normalized data ensures optimal conditions for training and evaluating the machine learning model.

# Model Building
We will build a Convolutional Neural Network (CNN) using Keras. The architecture will consist of two convolutional layers followed by max pooling layers, a dropout layer for regularization, and a dense softmax output layer. This CNN structure is designed to effectively capture spatial hierarchies and patterns in the image data.

# Model Training
We compile the model using the Adam optimizer and categorical crossentropy loss. We then train the model on the training data for 5 epochs with a batch size of 128.

# Model Evaluation
After training, we evaluate the model on the test dataset to determine its performance.

The members of the group are:
- [Pujita sunnapu](https://www.linkedin.com/in/pujitasunnapu)
- [Yash Raythatha](https://www.linkedin.com/in/yashrayththa/)
- [Jill Kakadiya](https://www.linkedin.com/in/jill-kakadiya-458600222)
- [Nitya Shah](https://www.linkedin.com/in/nitya-shah2043/)
