# Facial Expression Recognition

This project implements facial expression recognition using neural networks in Python, based on machine learning and image processing techniques.

## Overview

- **Purpose:** Detect and classify facial expressions from grayscale images
- **Approach:** Features custom implementations of Logistic Regression and an Artificial Neural Network (ANN) from scratch for both binary and multi-class facial expression classification.

## Dataset

- Uses the [FER-2013](https://www.kaggle.com/datasets/msambare/fer2013) dataset
  - Images are 48x48 pixel grayscale, flattened to vectors of length 2304
  - Labels include multiple expression categories; code supports both binary (e.g., happy/sad) and multi-class tasks.
- Dataset CSV must be in your working directory (`fer2013.csv`).

## Requirements

- Python 3.x
- Packages:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
