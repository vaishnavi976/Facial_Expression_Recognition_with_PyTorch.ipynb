# Facial Expression Recognition Using PyTorch




## Overview
This repository contains code for a facial expression recognition model implemented using PyTorch. The goal of this project is to accurately classify facial expressions into categories such as happy, sad, angry, surprised, etc., based on images of human faces.

## Features
Deep Learning with PyTorch: Uses PyTorch for building and training the neural network.

Facial Expression Recognition: Classifies images of faces into multiple expression categories.

Data Augmentation: Includes techniques like random horizontal flip, rotation, and more.

Model Checkpointing: Save and load models during training.
GPU Support: Leverages GPU acceleration for faster training.
## Model Architecture
The model is a convolutional neural network (CNN) based on the ResNet18 architecture, with modifications to accommodate facial expression recognition. 

It includes the following layers:

Convolutional Layers: To extract features from the input images.

Pooling Layers: To reduce spatial dimensions.

Fully Connected Layers: For classification into different facial expression categories.

Softmax Layer: To output the probability distribution across the expression classes.
