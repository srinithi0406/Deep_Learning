# Deep Learning Laboratory (CS3807)

This repository contains the implementations for the Deep Learning Laboratory experiments.

## Experiment 1: Single Layer Perceptron for Binary Classification

- **Objective:** Implement a Single Layer Perceptron from scratch to perform binary classification.
- **Model Used:** Single Layer Perceptron with a Step Activation Function.
- **Dataset:** [Banknote Authentication Dataset](https://archive.ics.uci.edu/dataset/267/banknote+authentication) (UCI Machine Learning Repository)
- **Dataset Description:** The dataset contains 1,372 instances and 4 numerical features (Variance, Skewness, Curtosis, Entropy) extracted from images of genuine and forged banknote-like specimens. The task is a binary classification problem to predict whether a banknote is authentic (Class 0) or forged (Class 1).

## Experiment 2: Multi-Layer Perceptron (MLP) for Multi-Class Image Classification

- **Objective:** Implement an MLP using TensorFlow/Keras to perform multi-class image classification.
- **Model Used:** Multi-Layer Perceptron (MLP) with ReLU activation for hidden layers and Softmax for the output layer.
- **Dataset:** Fashion-MNIST
- **Dataset Description:** Fashion-MNIST is a dataset of Zalando's article images, consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image associated with a label from 10 classes (representing different types of clothing and fashion items).

## Experiment 3: Implementation of Convolutional Neural Networks (CNNs) for Image Classification

- **Objective:** Understand the working principles of CNNs by implementing convolution, pooling, feature map visualization, and building an image classifier.
- **Model Used:** Custom Convolutional Neural Network.
- **Dataset:** CIFAR-10
- **Dataset Description:** A dataset of 60,000 32x32 color images in 10 classes, with 6,000 images per class (50,000 training and 10,000 test images).

## Experiment 4: Comparative Study of Deep CNN Architectures Using Transfer Learning

- **Objective:** Study the evolution of deep CNN architectures and implement transfer learning by fine-tuning pretrained models.
- **Model Used:** Pretrained CNN models (e.g., VGG16, ResNet50, MobileNetV2) modified with custom classification heads.
- **Dataset:** CIFAR-10
- **Dataset Description:** A dataset of 60,000 32x32 color images in 10 classes (50,000 training and 10,000 test images).

## Experiment 5: Comprehensive Study of CNN Training and Optimization

- **Objective:** Systematically study weight initialization, regularization, optimizers, hyperparameter tuning, transfer learning, and cross-validation on CNN performance.
- **Model Used:** MobileNetV2 (pretrained on ImageNet).
- **Dataset:** Oxford-IIIT Pet Dataset
- **Dataset Description:** A dataset containing images of cats and dogs belonging to 37 different breeds, resized to 224x224x3 for model compatibility.
