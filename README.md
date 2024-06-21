# Brain Tumor Classification using Convolutional Neural Networks (CNNs)

## Overview

This project utilizes Convolutional Neural Networks (CNNs) to classify brain tumor images into two categories: 'No' (no tumor) and 'Yes' (tumor present). It covers data preprocessing, model building, training, evaluation, and predictions using TensorFlow and Keras.

## Key Features

- **Data Preprocessing**: Images are augmented using techniques like rescaling, shearing, zooming, and horizontal flipping.
- **Model Architecture**: The CNN consists of convolutional layers, max-pooling, flattening, dense layers, and a sigmoid output layer.
- **Training**: The model is trained on a labeled dataset using the Adam optimizer and binary cross-entropy loss function.
- **Evaluation**: Performance metrics such as accuracy are evaluated after training.
- **Predictions**: New images can be classified as either 'No' or 'Yes' based on the trained model.

## Installation

Ensure you have Python 3.x installed along with the following dependencies:

- TensorFlow 2.x
- NumPy
- Matplotlib
- scikit-learn

Install dependencies using pip:

```bash
pip install tensorflow numpy matplotlib scikit-learn
