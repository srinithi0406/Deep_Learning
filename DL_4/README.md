# Experiment 4: Comparative Study of Deep CNN Architectures Using Transfer Learning

## Objective
To study the evolution of deep CNN architectures (like LeNet-5, AlexNet, VGG16, GoogleNet, and ResNet) and implement transfer learning by fine-tuning pretrained CNN models for image classification.

## Dataset
**CIFAR-10 Dataset**
- **Training Images:** 50,000
- **Testing Images:** 10,000
- **Classes:** 10 (Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck)
- **Image Size:** 32 × 32 × 3 (RGB)

## Tasks Performed
1. **Dataset Preparation:** Load and normalize the CIFAR-10 dataset.
2. **Transfer Learning:** Utilize pretrained CNN models with ImageNet weights (e.g., VGG16, ResNet50, MobileNetV2). The original classifier is removed, the convolutional base is frozen, and a new custom classification head (GlobalAveragePooling + Dense layers) is added.
3. **Model Training:** Train the modified model using the Adam optimizer and Categorical Cross Entropy loss.
4. **Fine-Tuning:** Unfreeze the last convolution block of the pretrained model and continue training to improve performance. Compare accuracies before and after fine-tuning.
5. **Model Evaluation:** Evaluate the models using standard metrics (Accuracy, Precision, Recall, F1-score) and confusion matrices.
6. **Hyperparameter Study:** Compare model performance across different hyperparameter settings (Learning Rate, Batch Size, Optimizers, etc.).

## Models Used
- **Pretrained Bases:** VGG16, ResNet50, MobileNetV2, or EfficientNetB0 (using ImageNet weights).
- **Classification Head:** Global Average Pooling -> Dense (ReLU) -> Dense (Softmax).
