# Experiment 3: Implementation of Convolutional Neural Networks (CNNs) for Image Classification

## Objective
To understand the working principles of Convolutional Neural Networks by implementing convolution, pooling, feature map visualization, and image classification.

## Dataset
**CIFAR-10 Dataset**
- **Training Images:** 50,000
- **Testing Images:** 10,000
- **Classes:** 10
- **Image Size:** 32 × 32 × 3 (RGB)

## Tasks Performed
1. **Dataset Preparation:** Load and analyze the CIFAR-10 dataset (dimensions, class distribution).
2. **Convolution Operation:** Implement convolution layers and compare the effects of different kernel sizes (3x3, 5x5, 7x7).
3. **Hyperparameter Study:** Analyze the impact of different strides (1, 2) and padding techniques (Same, Valid).
4. **Feature Map Visualization:** Extract and visualize the feature maps after the first convolution layer.
5. **Pooling Techniques:** Compare the outputs and accuracies of Max Pooling versus Average Pooling.
6. **CNN Construction & Training:** Build a full CNN architecture and train it using the Adam optimizer.
7. **Model Evaluation:** Evaluate the trained model using various metrics (Accuracy, Precision, Recall, F1-score) and generate a confusion matrix.

## Model Architecture
The implemented custom Convolutional Neural Network follows this architecture:
`Input -> Conv -> ReLU -> MaxPool -> Conv -> ReLU -> MaxPool -> Flatten -> Dense -> Softmax`
