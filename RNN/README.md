# Machine Learning and Deep Learning with RNNs

This repository contains three distinct projects focusing on Recurrent Neural Networks (RNNs) and Sequence-to-Sequence (Seq2Seq) models for tasks related to Natural Language Processing (NLP). Each project demonstrates a different application of these powerful models, including sequence generation, machine translation, and text classification.

---

## Projects Overview

### 1. **Generation**

- **Category**: Natural Language Processing (NLP) - Sequence Generation
- **Description**:
  - This project uses a character-level Recurrent Neural Network (RNN) to generate sequences, such as names, based on a given category (e.g., language of origin). The model predicts the next character in a sequence iteratively.
- **Key Features**:
  - Generates realistic names from different languages.
  - Pre-trained on datasets of names categorized by language.
  - Implements a simple RNN architecture with dropout for variety in generation.
- **Dataset**: Names dataset, available at [PyTorch Tutorials](https://download.pytorch.org/tutorial/data.zip).

---

### 2. **Translation**

- **Category**: Natural Language Processing (NLP) - Machine Translation
- **Description**:
  - This project implements a Sequence-to-Sequence (Seq2Seq) model with attention for translating text from French to English. The attention mechanism helps the model focus on specific parts of the input sequence during translation.
- **Key Features**:
  - Uses a Seq2Seq model architecture with an encoder-decoder design.
  - Integrates an attention mechanism for improved translation accuracy.
  - Demonstrates how to handle paired datasets for machine translation tasks.
- **Dataset**: English-to-French translation pairs, available at [ManyThings.org](http://www.manythings.org/anki/).

---

### 3. **Classification**

- **Category**: Natural Language Processing (NLP) - Text Classification
- **Description**:
  - This project classifies names into categories (e.g., predicting the language of origin for a given name) using a character-level RNN. The model processes each word character by character to determine the output category.
- **Key Features**:
  - Predicts the language of origin based on the spelling of names.
  - Processes variable-length input sequences with a single RNN model.
  - Includes training and evaluation on categorized datasets.
- **Dataset**: Names dataset, available at [PyTorch Tutorials](https://download.pytorch.org/tutorial/data.zip).

---
