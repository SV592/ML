# Logistic Regression Algorithm

This repository contains a Jupyter Notebook implementing a Logistic Regression algorithm. The notebook provides an end-to-end process for training and evaluating the model using datasets in CSV format.

## Features

- **Data Upload**: Enables uploading datasets directly in Google Colab.
- **Data Loading**: Includes a utility function (`load_logistic_regression_data`) to load training and testing datasets.
- **Visualization**: Uses `matplotlib` to plot and analyze model performance.
- **Progress Monitoring**: Incorporates `tqdm` for progress tracking during model training.
- **Custom Implementation**: Implements the Logistic Regression algorithm using only core libraries (`numpy`, `matplotlib`, `tqdm`).

## Setup

### Requirements:
- **Python**: Version 3.7+
- **Libraries**:
  - `numpy`
  - `matplotlib`
  - `tqdm`

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

1. Open the notebook in Google Colab or a local Jupyter Notebook environment.
2. Run the cells sequentially:
   - **Data Upload**: Upload files if running on Google Colab.
   - **Library Import**: Import the required libraries.
   - **Data Loading**: Use the `load_logistic_regression_data` function to load datasets.
   - **Model Training**: Follow the provided steps to train and evaluate the Logistic Regression model.
3. Visualize the results and analyze model performance.

## Functions

### `load_logistic_regression_data`
Loads the training and testing datasets from local storage.

**Outputs**:
- `train_inputs`: `numpy` array of training data points with features.
- `train_labels`: `numpy` array of training labels.
- `test_inputs`: `numpy` array of test data points with features.
- `test_labels`: `numpy` array of test labels.
