# Iris and MNIST Dataset Analysis

This repository contains code and analyses for two well-known datasets: Iris and MNIST. The project demonstrates various data preprocessing, visualization, and machine learning techniques using Python libraries.

## Project Overview

### 1. Iris Dataset Analysis

The Iris dataset consists of measurements of iris flowers across different species. The analysis includes:

- **Data Visualization**: Scatter plots are generated to visualize the relationship between sepal length and sepal width, and petal length and petal width. These plots help in understanding the distribution and separation of different species.
- **Feature Scaling**: The dataset is normalized using Min-Max Scaling and Robust Scaling. Normalization is crucial for preparing data for machine learning algorithms.
- **Feature Statistics**: Summary statistics for selected features (sepal length and sepal width) are computed to understand their distributions.

### 2. MNIST Dataset Analysis

The MNIST dataset contains images of handwritten digits. The analysis covers:

- **Class Distribution**: Visualizations of the class distribution in both the training and test sets are provided to show the balance of the dataset.
- **Data Preprocessing**: Images are flattened and normalized to prepare them for training a neural network. One-hot encoding is applied to the labels.
- **Neural Network Training**: A simple neural network is built and trained using TensorFlow/Keras. The model's performance is evaluated on the test set, with training and validation losses and accuracies plotted.
- **Confusion Matrix**: A confusion matrix is visualized to show how well the model performs on each digit class, highlighting the correct and incorrect classifications.

## Dependencies

The project requires the following Python libraries:
- pandas
- scikit-learn
- matplotlib
- numpy
- tensorflow
- keras
- seaborn



## Acknowledgments

- Iris dataset: UCI Machine Learning Repository
- MNIST dataset: Yann LeCun's website

