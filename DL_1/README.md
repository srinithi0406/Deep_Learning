# Experiment 1: Single Layer Perceptron for Binary Classification

## Objective
The objective of this experiment is to understand the concept of an artificial neuron and implement a Single Layer Perceptron from scratch for binary classification. The experiment involves understanding the perceptron learning algorithm, the importance of activation functions, visualizing the learning process, and evaluating the classifier using a real-world dataset.

## Dataset Details
- **Dataset:** [Banknote Authentication Dataset](https://archive.ics.uci.edu/dataset/267/banknote+authentication) (UCI Machine Learning Repository)
- **Instances:** 1,372
- **Features:** 4 Numerical Features (Variance, Skewness, Curtosis, Entropy)
- **Classes:** 2 (0 – Authentic Banknote, 1 – Forged Banknote)
- **Missing Values:** None
- **Task:** Binary Classification

## Model Used
- **Architecture:** Single Layer Perceptron
- **Activation Function:** Step Activation Function
- **Learning Algorithm:** Perceptron Learning Rule

## Tasks Performed
- Exploratory Data Analysis (EDA) and data visualization (Histograms, Heatmaps, Scatter Plots)
- Data Normalization and Train/Test split
- Perceptron Implementation from scratch (Weight/Bias initialization, Forward Propagation, Learning Rule)
- Model Training and Evaluation (Accuracy, Precision, Recall, F1-score, Confusion Matrix)
- Hyperparameter tuning (Learning Rates comparison)

## Experimental Results
The implemented Custom Single Layer Perceptron was evaluated and compared against Scikit-learn's built-in Perceptron module. Both achieved high performance on the Banknote Authentication Dataset:

**Custom Perceptron Results:**
- **Accuracy:** 98.55%
- **Precision:** 100.0%
- **Recall:** 96.85%
- **F1 Score:** 98.40%

**Scikit-learn Perceptron Results:**
- **Accuracy:** 97.45%
- **Precision:** 100.0%
- **Recall:** 94.49%
- **F1 Score:** 97.17%

## How to Run
1. Ensure you have Python installed along with the required libraries: `jupyter`, `numpy`, `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`.
2. Navigate to the `DL_1` directory in your terminal.
3. Start Jupyter Notebook:
   ```bash
   jupyter notebook "DL_1 (1).ipynb"
   ```
4. Open the notebook in your browser and run all cells (`Cell > Run All`) to load the data, train the perceptron models, and visualize the evaluation metrics.
