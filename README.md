# Task-2
# Readme File for German Traffic Sign Recognition
## Overview
This repository contains a Python script for a Convolutional Neural Network (CNN) model trained on the "GTSRB - German Traffic Sign Recognition Benchmark" dataset from Kaggle. The script uses TensorFlow and Keras for building and training the model, and it includes functionalities for data preprocessing, model training, evaluation, and prediction.

### Dataset
The dataset used for this project is the "GTSRB - German Traffic Sign Recognition Benchmark" available on Kaggle. It consists of images of traffic signs belonging to 43 different classes. The classes include various speed limits, warnings, and other traffic-related information. The dataset is split into training and testing sets.

Link to the dataset on Kaggle: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

## Project Structure
train.py: The main script containing the code for loading, preprocessing, and training the model.
test_image.png: An example image for testing the trained model.
training/data.npy: Numpy array file containing the preprocessed training data.
training/target.npy: Numpy array file containing the corresponding labels for the training data.
