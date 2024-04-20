# Neural Networks for Image Analysis
<img width="733" alt="NNCover" src="https://github.com/Torin99/Neural-Networks-Image-Analysis/assets/87572723/a46594b4-faea-4746-9d3f-c7c8424b174a">

This repository contains the implementation of Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) for image analysis tasks using the CIFAR-10 dataset.

## Table of Contents

- [Dataset Overview](#dataset-overview)
- [Artificial Neural Network (ANN) Implementation](#artificial-neural-network-implementation)
- [Convolutional Neural Network (CNN) Implementation](#convolutional-neural-network-implementation)
- [Model Evaluations](#model-evaluations)
- [Conclusion](#conclusion)

## Dataset Overview

The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 classes: 'Plane', 'Car', 'Bird', 'Cat', 'Deer', 'Dog', 'Frog', 'Horse', 'Ship', and 'Truck'. Each class contains 6,000 images distributed between training and testing sets.

## Artificial Neural Network (ANN) Implementation

The ANN implementation involves a model with 4 fully connected layers, ReLU activation functions, and Stochastic Gradient Descent (SGD) optimizer. The model is trained over 10 epochs, achieving an accuracy of 51% on the test images.

## Convolutional Neural Network (CNN) Implementation

The CNN architecture comprises two convolutional layers followed by three fully connected layers. ReLU activation functions are applied after each layer, with a MaxPooling layer for downsampling. The model is trained for 10 epochs, achieving an accuracy of 63% on the test images.

## Model Evaluations

Both models were evaluated based on loss curves, accuracy per class, and overall accuracy on the test set. The CNN outperformed the ANN with an overall accuracy of 63% compared to 51%.

## Conclusion

In conclusion, the CNN model demonstrated superior performance for image classification tasks on the CIFAR-10 dataset compared to the ANN model. Further exploration could involve experimenting with different optimization functions, image preprocessing techniques, or model architectures.
