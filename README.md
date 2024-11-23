# Convolutional Neural Network (CNN) for FashionMNIST

Welcome to the Convolutional Neural Network (CNN) project for classifying fashion items using the FashionMNIST dataset! This project utilizes a CNN architecture to classify images of clothing items into various categories such as T-shirts, dresses, shoes, and more.

## Dataset

The dataset used in this project is the FashionMNIST dataset, which is available in the torchvision library. FashionMNIST is a dataset of Zalando's article images consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a grayscale image of size 28x28 pixels, belonging to one of 10 categories.

## Helper Functions

The `helper_functions.py` file contains utility functions for evaluating the accuracy metrics of the CNN model. These functions may include calculating accuracy, precision, recall, F1-score, and confusion matrix, among others.

## Model Saving

The trained CNN model is saved in the `model/` directory. This directory contains the saved model weights and architecture in a format compatible with PyTorch's `torch.save()` function.

## Jupyter Notebook

The `CNN_FASHION_MNIST.ipynb` notebook is where the entire CNN project is implemented. In this notebook, you will find code for data preprocessing, model architecture definition, model training, evaluation, and visualization of results.

## Repository Structure

- `model/`: Directory to save the trained CNN model.
- `helper_functions.py`: Python file containing helper functions for accuracy metrics.
- `CNN_FASHION_MNIST.ipynb`: Jupyter notebook containing the CNN implementation for the FashionMNIST dataset.
- `README.md`: This file, providing an overview of the project and instructions for usage.

