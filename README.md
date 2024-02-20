# MNIST-S5
MNIST dataset trained on PyTourch Module through Colab

# Convolutional Neural Network for Image Classification

## Overview

This repository contains code for a Convolutional Neural Network (CNN) implemented in PyTorch for image classification. The CNN architecture is defined in the `model.py` file, and utility functions for training and testing the model, as well as data transformations, are provided in the `utils.py` file. The `S5.ipynb` notebook demonstrates the usage of the model for training and evaluation.

## Files

### 1. `model.py`

This file defines the neural network architecture using PyTorch. The `Net` class is a simple CNN with convolutional layers followed by fully connected layers. The forward method implements the forward pass through the network.

### 2. `utils.py`

This file contains utility functions for training and testing the model. Functions include device setup, visualization of training data, counting correct predictions, and training/test procedures. Additionally, data transformation functions for training and testing are provided.

### 3. `S5.ipynb`

This Jupyter notebook demonstrates the usage of the model for training and evaluation. It includes sections for loading data, model instantiation, training, testing, and visualizing the results.

## Usage

1. **Model Training:**
   - Open the `S5.ipynb` notebook.
   - Execute the cells in the notebook sequentially for loading data, defining the model, training, and testing.

2. **Customization:**
   - Adjust hyperparameters, model architecture, or training configurations in the notebook as needed.

3. **Visualization:**
   - Visualize training and test results using the provided utility function `show_train_test_result` in the `utils.py` file.

## Dependencies

- Python 3.x
- PyTorch
- Matplotlib
- tqdm

## Acknowledgments

The code in this repository is inspired by practical implementations of convolutional neural networks for image classification tasks.

