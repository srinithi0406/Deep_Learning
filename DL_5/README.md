# Experiment 5: Comprehensive Study of CNN Training and Optimization

## Objective
To systematically study the effects of weight initialization, regularization, optimization algorithms, hyperparameter tuning, transfer learning, and cross-validation on CNN image classification performance.

## Dataset
**Oxford-IIIT Pet Dataset**
- **Content:** Images of cats and dogs belonging to 37 different breeds.
- **Image Size:** Resized to 224 × 224 × 3 (RGB) to be compatible with MobileNetV2.

## Tasks Performed
1. **Weight Initialization:** Compare the convergence of Zero, Random, Xavier/Glorot, and He initializations.
2. **Regularization:** Investigate overfitting by comparing No Regularization, L2 Regularization, Dropout, and Batch Normalization.
3. **Optimization Algorithms:** Evaluate and compare the performance of SGD, Momentum, RMSProp, and Adam optimizers.
4. **Hyperparameter Tuning:** Study the effects of varying the learning rate, batch size, dropout rate, and optimizer choice.
5. **Transfer Learning & Fine-Tuning:** Use a pretrained MobileNetV2 model (ImageNet weights). Compare Feature Extraction (freezing the base) vs. Fine-Tuning (unfreezing selected layers and training with a small learning rate).
6. **K-Fold Cross-Validation:** Apply 5-fold cross-validation on the most promising configurations to select the best hyperparameter setup based on mean accuracy and standard deviation.
7. **Final Model Evaluation:** Train the selected model on the full training set and evaluate it on an independent, untouched test set using Accuracy, Precision, Recall, F1-score, and a Confusion Matrix.

## Model Used
- **Architecture:** MobileNetV2 (pretrained on ImageNet).
