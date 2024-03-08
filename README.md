# Image Classification Project with VGG16.

This repository contains an image classification project using the VGG16 architecture with Keras and TensorFlow. The model is trained to distinguish between images of cats and dogs.

## Project Structure

- **`app.py`**: Contains the main code that defines, compiles, and trains the VGG16 model.
- **`requirements.txt`**: List of dependencies needed to run the project.

## Requirements

Make sure to have all dependencies installed. You can do this by executing the following command:

## Model Visualization
A summary of the VGG16 model is provided using model.summary() in the code.

## Warnings
The fit_generator function used for training is deprecated. It is recommended to use fit instead.

The warning about the period argument being deprecated suggests using save_freq instead.

The warning about the deprecation of lr in the optimizer indicates that you should use learning_rate instead of lr.
