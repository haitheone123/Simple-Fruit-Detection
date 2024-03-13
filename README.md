# **Deep learning Project - RNN/LSTM/GRU on LSA64 Dataset**

## Introduction
This project implements a RNN/LSTM/GRU model on the LSA64 dataset. 

## Dataset
The LSA64 dataset consists of images depicting sign language in Argentinian, each labeled with one of 64 categories. The dataset is split into training, validation, and test sets for model evaluation.
Further information can be found [here](http://facundoq.github.io/datasets/lsa64/).

## Model Architecture
Feature extractor: InceptionV3 (from Keras)
Classification model: Gate Recurrent Unit (GRU)

## Requirements
- Python 3.10
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
