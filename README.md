# Handwritten Digital Classification using TensorFlow and Keras
This repository contains code for building a neural network model using TensorFlow and Keras to classify hand-written digits from the MNIST dataset. MNIST (Modified National Institute of Standards and Technology) is a widely-used dataset for training and testing machine learning models, specifically in the field of computer vision. The MNIST dataset consists of 28x28 pixel grayscale images of handwritten digits (0 to 9), along with their corresponding labels.

![Representation-of-value-three-in-the-MNIST-dataset-and-its-equivalent-matrix](https://github.com/MihirLodaya/Handwritten-Digit-Classification/assets/154822670/3225c083-0ff5-4a32-99fc-b1899ad9dab5)

# Model Architecture
The neural network model consists of:

  Input layer: Flatten layer to convert 2D image arrays (28x28 pixels) into 1D arrays (784 pixels).

  Hidden layer: Dense layer with 128 neurons and ReLU activation function.

  Output layer: Dense layer with 10 neurons (one for each digit) and softmax activation function.

![HDC_NN](https://github.com/MihirLodaya/Handwritten-Digit-Classification/assets/154822670/40d66c70-7a42-4629-a839-2c7ea6cb200a) 

# Results:
The trained model achieves an accuracy of 97.45% on the test dataset, indicating its effectiveness in recognizing handwritten digits.

