# Mango Image Classification

This repository contains code for processing images of mangoes and classifying them into two categories: diseased and healthy. The code is written in Python using the Keras library for deep learning.

## Getting Started

To use this code, you will need to have Python 3 installed on your computer, as well as the following libraries:

- TensorFlow
- Keras
- Matplotlib

You can install these libraries using pip, like so:

```shell
pip install tensorflow keras matplotlib
```

Once you have the necessary libraries installed, you can run the code by executing the `main.py` file. This will train the model on the provided dataset and output the results.

## Dataset

The dataset used for this project consists of images of mangoes that have been labeled as either diseased or healthy. The images are stored in the `Mango` directory, which contains two subdirectories: `diseased` and `healthy`. The images are preprocessed using the Keras `ImageDataGenerator` class, which resizes and rescales the images and splits them into training, validation, and testing sets.

## Model

The model used for this project is a convolutional neural network (CNN) with several layers of convolution and pooling, followed by a few fully connected layers. The model is trained using the Adam optimizer and categorical cross-entropy loss. After training, the model is evaluated on the testing set, and the results are output to the console.

## Results

The model achieves an accuracy of around 90% on the testing set, which is a good result considering the simplicity of the model and the small size of the dataset. However, there is still room for improvement, and future work could involve experimenting with different architectures and hyperparameters to achieve better results.

## Acknowledgments

This project was inspired by the work of [Chandrashekhar](https://github.com/chandrashekhar4u/Mango-Disease-Classification), who created a similar project using a different dataset and model architecture.
