#  Handwritten Digit Classification using MLP in TensorFlow

This project demonstrates how to classify handwritten digits from the **MNIST dataset** using a **Multi-Layer Perceptron (MLP)** built with **TensorFlow** and **Keras**. It walks through the complete deep learning pipeline — from data loading and preprocessing to model building, training, evaluation, and visualization — all within a single Jupyter Notebook.

---

##  Project Overview

-  **Dataset**: MNIST (70,000 grayscale images of digits 0–9, size 28×28)
-  **Model**: Multi-Layer Perceptron with 3 hidden layers (128 → 64 → 32 neurons)
-  **Preprocessing**:
  - Pixel value normalization to [0, 1]
  - Flattening 2D images to 1D vectors
  - One-hot encoding of labels
-  **Training**:
  - Optimizer: Adam
  - Loss Function: Categorical Crossentropy
  - Epochs: 10
-  **Test Accuracy**: ~97.7%
-  **Visualizations**:
  - Training vs Validation Accuracy & Loss curves
  - Confusion Matrix heatmap
  - Sample predictions with true and predicted labels

---

##  Tech Stack

| Tool             | Purpose                           |
|------------------|-----------------------------------|
| Python           | Programming language              |
| TensorFlow / Keras | Deep learning model creation      |
| NumPy            | Numerical operations              |
| Matplotlib       | Plotting accuracy and loss        |
| Seaborn          | Visualizing confusion matrix      |
| scikit-learn     | Evaluation metrics and reports    |

---

##  Files in the Repository

- `Handwritten_Digit_Classification.ipynb` – Complete notebook with code, output, and visualizations
- `README.md` – Project overview and documentation
