# Experiment 2: Multi-Layer Perceptron (MLP) for Multi-Class Image Classification

## Objective
Implement an MLP using TensorFlow/Keras on the Fashion-MNIST dataset. The experiment covers image preprocessing, flattening, model construction, training, evaluation, and automated hyperparameter optimization.

## Dataset Details
- **Dataset:** Fashion-MNIST
- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Classes:** 10
- **Image Size:** 28x28 (Grayscale)
- **Task:** Multi-Class Image Classification

## Model Used
- **Architecture:** Multi-Layer Perceptron (MLP)
- **Recommended Hidden Layers:** Dense layers with ReLU activation (e.g., 128 neurons, 64 neurons)
- **Output Layer:** Dense layer with Softmax activation (10 neurons for the 10 classes)
- **Framework:** TensorFlow / Keras

## Tasks Performed
- Image Preprocessing (Flattening and Pixel Normalization to [0, 1])
- Model Construction and Training using Adam optimizer and Categorical Cross Entropy loss
- Model Evaluation (Accuracy, Precision, Recall, F1-score, Confusion Matrix)
- Automated Hyperparameter Optimization using GridSearchCV or RandomizedSearchCV (SciKeras wrapper)
- Visualization of Learning Curves (Accuracy/Loss vs Epochs) and Search Results

## Experimental Results
The Multi-Layer Perceptron was evaluated on the Fashion-MNIST test set before and after hyperparameter tuning:

**Baseline Model Performance:**
- **Accuracy:** 88.98%
- **Precision:** 89.07%
- **Recall:** 88.98%
- **F1-score:** 88.78%

**Optimized Model Performance:**
- **Best Hyperparameters:** Optimizer: `rmsprop`, Learning Rate: `0.001`, Hidden Layers: `2`, Hidden Neurons: `128`, Activation: `sigmoid`, Dropout Rate: `0.2`, Epochs: `30`, Batch Size: `128`
- **Cross-Validation Accuracy:** 89.01%
- **Test Accuracy:** 88.22%
- **Test Precision:** 88.32%
- **Test Recall:** 88.22%
- **Test F1-score:** 88.11%

*(Note: The optimized model performed very similarly to the baseline on the final test set)

## How to Run
1. Ensure you have Python installed along with the required libraries: `jupyter`, `tensorflow` (or `keras`), `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, and `scikeras`.
2. Navigate to the `DL_2` directory in your terminal.
3. Start Jupyter Notebook:
   ```bash
   jupyter notebook "DL_2 (1).ipynb"
   ```
4. Open the notebook in your browser and run all cells (`Cell > Run All`) to download the Fashion-MNIST dataset, preprocess the images, build the MLP, run the hyperparameter search, and evaluate the final model.
