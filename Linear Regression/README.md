# Linear Regression Algorithm

This repository contains a Jupyter Notebook that demonstrates the implementation of a Linear Regression algorithm. The notebook provides a simple and customizable framework to train and evaluate a linear regression model using data provided in CSV format.

## Features

- **Data Upload**: Allows for uploading data files directly in Google Colab.
- **Data Loading**: A utility function (`load_linear_regression_data`) is provided to load datasets into memory.
- **Visualization**: Uses `matplotlib` to plot and analyze model performance.
- **Custom Implementation**: Builds a Linear Regression model using only core libraries (`numpy`, `matplotlib`).

## Setup

### Requirements:
- **Python**: Version 3.7+
- **Libraries**:
  - `numpy`
  - `matplotlib`

### Run the Notebook:
- **If using Google Colab**:
  1. Upload the required data files (`train_inputs.csv`, `train_targets.csv`, `test_inputs.csv`, `test_targets.csv`) when prompted.
- **If running locally**:
  1. Ensure the dataset files are in the same directory as the notebook.

### File Descriptions:
- `train_inputs.csv`: Training data with features.
- `train_targets.csv`: Corresponding targets for the training data.
- `test_inputs.csv`: Test data with features.
- `test_targets.csv`: Corresponding targets for the test data.

## How to Use

1. Open the notebook in your environment (Google Colab or local Jupyter Notebook).
2. Run the cells sequentially:
   - **Data Upload**: Upload files if running on Google Colab.
   - **Library Import**: Ensure the necessary libraries are installed.
   - **Data Loading**: Use the `load_linear_regression_data` function to load datasets.
   - **Model Training**: Follow the provided steps to train and evaluate the Linear Regression model.
3. Visualize the results and analyze model performance.

## Functions

### `load_linear_regression_data`
Loads the training and testing datasets from local storage.

**Outputs**:
- `train_inputs`: `numpy` array of training data points with features.
- `train_targets`: `numpy` array of training targets.
- `test_inputs`: `numpy` array of test data points with features.
- `test_targets`: `numpy` array of test targets.
