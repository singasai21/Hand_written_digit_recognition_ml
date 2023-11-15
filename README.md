
# Handwritten Digit Recognition with Fully Connected Neural Network

## Project Overview

This project focuses on handwritten digit recognition using a fully connected neural network. The dataset utilized is the MNIST dataset, and the goal is to train a model capable of accurately classifying digits from 0 to 9.

## Setup Instructions

1. **TensorFlow Installation:**
   - Download and install TensorFlow from [TensorFlow Install Guide](https://www.tensorflow.org/install/install_sources) or using the command `sudo pip install tensorflow`.

2. **Alternative Library (Optional):**
   - Alternatively, you can use the Keras library for building and training neural networks.

3. **MNIST Dataset Download:**
   - Use the provided code to download the MNIST dataset. TensorFlow and Keras versions are available.

4. **Data Preprocessing:**
   - Reduce training size by 1/10 if computational resources are limited.
   - Define a radial basis function (RBF) and convert 28x28 images into 32x32 using RBF transformation.

5. **Model Training:**
   - Run fully connected neural networks with different hyperparameter combinations, including the number of hidden layers, activation functions, and dropout rates.

6. **Performance Evaluation:**
   - Plot graphs for loss vs. epoch and accuracy (train, validation) vs. epoch for all configurations.

7. **Optimizer Learning Rate Experiment:**
   - Vary the Adam optimizer learning rate and record the time to achieve the best validation accuracy for each run.

8. **Personal Handwritten Digits Testing:**
   - Create five images (size 28x28) containing digits of your own handwriting and test the trained classifier's predictions.

## File Descriptions

- `mnist_fcnn.ipynb`: Jupyter notebook containing the implementation of the fully connected neural network for digit recognition.
- `rbf_transformation.py`: Python script for RBF transformation of images.

## Results and Analysis

- The project achieved notable accuracy in digit recognition with various hyperparameter configurations.
- Optimizer learning rate experiments provide insights into the impact on training time and accuracy.

## Conclusion

This README provides an overview of the project, setup instructions, file descriptions, and key results. Feel free to explore the Jupyter notebook for a detailed walkthrough of the code and analysis.

For additional details, refer to the comprehensive report submitted with the project.

