# K-Nearest Neighbors (KNN) Algorithm

This repository contains a Jupyter Notebook that implements a K-Nearest Neighbors (KNN) algorithm. The notebook is designed to work with datasets provided in CSV format and demonstrates essential steps, including data loading, training, and testing the KNN model.

## Features

- **Data Upload**: Supports file uploads for users running the notebook in Google Colab.
- **Data Loading**: A utility function (`load_knn_data`) to load training and testing datasets into memory.
- **Visualization**: Uses `matplotlib` for plotting and visualizing results.
- **Customizable**: Implements the KNN algorithm using only core libraries (`numpy`, `matplotlib`).

## Setup

### Requirements:
- **Python**: Version 3.7+
- **Libraries**:
  - `numpy`
  - `matplotlib`

### Run the Notebook:
- **If using Google Colab**:
  1. Upload the required data files (`train_inputs.csv`, `train_labels.csv`, `test_inputs.csv`, `test_labels.csv`) when prompted.
- **If running locally**:
  1. Place the dataset files in the same directory as the notebook.

### File Descriptions:
- `train_inputs.csv`: Training data with features.
- `train_labels.csv`: Corresponding labels for the training data.
- `test_inputs.csv`: Test data with features.
- `test_labels.csv`: Corresponding labels for the test data.

## How to Use

1. Open the notebook in your environment of choice (Google Colab or local Jupyter Notebook).
2. Run the cells sequentially:
   - **Data Upload**: Upload files if running on Google Colab.
   - **Library Import**: Ensure the necessary libraries are installed.
   - **Data Loading**: Use the provided `load_knn_data` function to load datasets.
3. Follow additional instructions in the notebook to train and test the KNN model.

## Functions

### `load_knn_data`
Loads training and testing datasets from local storage.

**Outputs**:
- `train_inputs`: `numpy` array of training data points with features.
- `train_labels`: `numpy` array of training labels.
- `test_inputs`: `numpy` array of test data points with features.
- `test_labels`: `numpy` array of test labels.
