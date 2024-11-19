# Machine Learning Algorithms

This repository contains Jupyter Notebooks implementing various foundational machine learning algorithms. Each notebook is designed to be beginner-friendly, with detailed explanations and examples, making it suitable for both learning and experimentation.

## Included Algorithms

### 1. **K-Nearest Neighbors (KNN)**

- **Description**: Implements the KNN algorithm, a non-parametric method used for classification and regression.
- **Features**:
  - Custom implementation using `numpy`.
  - Data visualization with `matplotlib`.
  - Designed to work with CSV datasets.
- **Notebook**: [`KNN Algorithm.ipynb`](./KNN%20Algorithm.ipynb)
- **More Info**: [KNN README](./KNN/README.md)

---

### 2. **Linear Regression**

- **Description**: Implements Linear Regression for predicting a target variable based on input features.
- **Features**:
  - Simple and customizable framework.
  - Data visualization with `matplotlib`.
  - Works with CSV datasets for easy reproducibility.
- **Notebook**: [`Linear Regression Algorithm.ipynb`](./Linear%20Regression%20Algorithm.ipynb)
- **More Info**: [Linear Regression README](./Linear%20Regression/README.md)

---

### 3. **Logistic Regression**

- **Description**: Implements Logistic Regression for binary classification tasks.
- **Features**:
  - Progress tracking using `tqdm`.
  - Visualization of results with `matplotlib`.
  - Utilizes `numpy` for computations.
- **Notebook**: [`Logistic Regression Algorithm.ipynb`](./Logistic%20Regression%20Algorithm.ipynb)
- **More Info**: [Logistic Regression README](./Logistic%20Regression/README.md)

---

### 4. **Convolutional Neural Network (CNN)**

- **Category**: Computer Vision - Image Classification
- **Description**: Implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into 10 categories (e.g., planes, cars, birds, etc.).
- **Features**:
  - Two convolutional layers with ReLU activations and max-pooling.
  - Fully connected layers for classification.
  - Integrates GPU support for faster training.
  - Visualizes training and validation metrics.
- **Notebook**: [`cs480_winter23_asst3_cnn_cifar10.ipynb`](./cs480_winter23_asst3_cnn_cifar10.ipynb)


### 5. **Generation**

- **Category**: Natural Language Processing (NLP) - Sequence Generation
- **Description**: Implements a character-level RNN to generate sequences, such as names, based on a given category (e.g., language of origin). The model predicts the next character iteratively.
- **Features**:
  - Generates realistic names from different languages.
  - Pre-trained on datasets of names categorized by language.
  - Implements dropout to add variety in generation.
- **Notebook**: [`Generation.ipynb`](./Generation.ipynb)

---

### 6. **Translation**

- **Category**: Natural Language Processing (NLP) - Machine Translation
- **Description**: Implements a Sequence-to-Sequence (Seq2Seq) model with an attention mechanism to translate text from French to English.
- **Features**:
  - Encoder-Decoder architecture with attention.
  - Handles paired datasets for machine translation tasks.
  - Demonstrates translation with variable-length sequences.
- **Notebook**: [`Translation.ipynb`](./Translation.ipynb)

---

### 7. **Classification**

- **Category**: Natural Language Processing (NLP) - Text Classification
- **Description**: Uses a character-level RNN to classify words into categories (e.g., predicting the language of origin for a given name).
- **Features**:
  - Processes variable-length input sequences.
  - Predicts the language of origin based on the spelling of names.
  - Includes training and evaluation on categorized datasets.
- **Notebook**: [`Classification.ipynb`](./Classification.ipynb)

---

### 8. **Variational Autoencoder (VAE)**
- **Category**: Generative Modeling
- **Description**: Implements a Variational Autoencoder (VAE) for generating new samples based on input data by learning a latent representation.
- **Features**:
  - Encodes data into a latent space and decodes it to reconstruct data with added variability.
  - Includes reparameterization trick for gradient-based optimization.
  - Trained on the MNIST dataset for image generation.
- **Notebook**: [`VAE_Complete.ipynb`](./VAE_Complete.ipynb)

---

### 9. **Generative Adversarial Network (GAN)**
- **Category**: Generative Modeling
- **Description**: Implements a Generative Adversarial Network (GAN) consisting of a generator and discriminator that compete to produce realistic images.
- **Features**:
  - Generator network creates synthetic images.
  - Discriminator network evaluates the authenticity of images.
  - Trained on the MNIST dataset to generate realistic handwritten digits.
- **Notebook**: [`GAN Complete.ipynb`](./GAN%20Complete.ipynb)


## Setup Instructions

### Requirements

- Python 3.7+
- Libraries:
  - `numpy`
  - `matplotlib`
  - `tqdm` (for Logistic Regression)
  - `torch`
  - `torchvision`

### Installation

```bash
    pip install numpy matplotlib tqdm torch torchvision`
```

### Running the Notebooks

1. Clone this repository:
   ```bash
   git clone https://github.com/SV592/ML.git
   cd ML
   ```
