
**Overview**

In this project, we utilize extensive Data Science and Machine Learning techniques to understand and manipulate the famous dataset known as MNIST. The techniques involve Exploratory Data Analysis on the dataset for better understanding followed by pre-processing and training a neural network.


**What is mnist**

MNIST set is a large collection of handwritten digits. It is a very popular dataset in the field of image processing. It is often used for benchmarking machine learning algorithms.

MNIST is short for Modified National Institute of Standards and Technology database.

MNIST contains a collection of 70,000, 28 x 28 images of handwritten digits from 0 to 9.

The dataset is already divided into training and testing sets. We will see this later in the tutorial. The images in mnist dataset look like:

![image](https://github.com/AaqibbHasanie/Data-Analytics-and-Image-Prediction-with-MNIST-dataset/assets/103883753/b9c6f13f-b092-4ee1-ba5b-391cb575511a)

**About the Neural Network**

Here is a brief description of the neural network defined in the provided code:

The input layer has 784 nodes, which is the number of pixels in a flattened MNIST image.

There are 3 hidden layers with 200, 100, and 50 nodes, respectively. All use the ReLU activation function.

The output layer has 10 nodes, representing the 10 possible digits. It uses the softmax activation function to produce a probability distribution over the possible digits.

A neural network is a type of machine learning algorithm that is inspired by the structure and function of the human brain. The general concept behind neural networks is to use interconnected layers of artificial neurons to learn patterns in data. During the training process, the network is presented with examples of input-output pairs, and it adjusts the weights of the connections between the neurons to minimize the difference between its predicted outputs and the true outputs. Once trained, the network can be used to make predictions on new, unseen data.


**Important Files**

Here is a breakdown of the important files:

**Group1_EDA.ipynb:** This file contains all the EDA techniques that we utilized for our dataset.

**Medium_Article.docs:** This file contains the medium article that we submitted for this project.

**coding.ipynb:** This file contains all the pre-processing and model trainings that we performed for the mnist dataset.
