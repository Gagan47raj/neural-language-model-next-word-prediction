# Neural Language Model for Next-Word Prediction

## Overview

This project implements a simple neural language model using PyTorch for next-word prediction.

The model predicts the next word based on a fixed sequence of three preceding words using the Penn Treebank corpus available through NLTK.

## Objective

The objective is to develop and evaluate a neural language model consisting of:

* Word embedding layer
* One fully connected hidden layer
* Output layer for vocabulary prediction

The model learns the relationship between three consecutive words and the word that follows them.

## Dataset

**Penn Treebank Corpus**

The dataset is accessed using the NLTK library.

## Problem Statement

Given three preceding words:

```text
w1 w2 w3
```

the model predicts the next word:

```text
w4
```

For example:

```text
Input:
the company reported

Target:
strong
```

## Model Pipeline

```text
Penn Treebank
      ↓
Data Preprocessing
      ↓
Train/Test Split
      ↓
Vocabulary Construction
      ↓
Word-to-Index Mapping
      ↓
3-Word Sequence Generation
      ↓
Embedding Layer
      ↓
Fully Connected Hidden Layer
      ↓
Output Layer
      ↓
Next-Word Prediction
      ↓
Evaluation
```

## Technologies

* Python
* PyTorch
* NLTK
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

## Project Structure

```text
neural-language-model-next-word-prediction/
│
├── GroupX_PennTreebank/
│   └── GroupX_PennTreebank.ipynb
│
└── README.md
```

## Assignment

**Problem Statement 7: Neural Language Model for Next-Word Prediction**

The implementation includes:

1. Data preprocessing and sequence generation
2. Vocabulary construction
3. Neural language model
4. Training
5. Predictions for at least 10 test sequences
6. Evaluation
7. Observations and conclusion

## Current Progress

* [x] Project setup
* [x] PyTorch environment verification
* [x] Penn Treebank dataset loading
* [x] Data preprocessing
* [x] Fixed train/test split
* [ ] Vocabulary construction
* [ ] Sequence generation
* [ ] PyTorch Dataset and DataLoader
* [ ] Neural language model
* [ ] Model training
* [ ] Test predictions
* [ ] Evaluation
* [ ] Observations and conclusion

## Reproducibility

A fixed random seed is used for reproducible experimentation.

```python
SEED = 42
```

## Author

**Name:** Your Name
**Group:** Group X
