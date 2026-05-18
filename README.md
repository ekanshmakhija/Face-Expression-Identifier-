# Facial Expression Recognition using ResNet18

## Overview

This project performs Facial Expression Recognition using Deep Learning and Transfer Learning with the ResNet18 architecture. The model classifies facial expressions from images into different emotion categories.

The notebook includes dataset loading, preprocessing, data augmentation, model training, and evaluation using PyTorch.

---

# Features

* Image preprocessing and augmentation
* Transfer Learning using ResNet18
* Facial expression classification
* GPU support using PyTorch
* Training and validation pipeline
* Accuracy evaluation

---

# Emotion Classes

The model is trained to classify facial expressions into 7 categories:

* Angry
* Disgust
* Fear
* Happy
* Neutral
* Sad
* Surprise

---

# Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib
* PIL
* Jupyter Notebook

---

# Deep Learning Model

This project uses:

* ResNet18 (Pretrained)
* Transfer Learning
* Adam Optimizer
* Cross Entropy Loss

---

# Dataset

Dataset used:

Facial Expression Recognition Dataset (FER)

The dataset contains training and testing images for different facial emotions.

---

# Data Augmentation Techniques

The following augmentation methods are used:

* Random Horizontal Flip
* Random Rotation
* Color Jitter
* Tensor Conversion

---

# Installation

Install the required libraries:

```bash
pip install torch torchvision numpy matplotlib pillow jupyter
```

---

# Running the Project

Open the notebook:

```bash
jupyter notebook face-exp-resnet(2).ipynb
```

Run all cells to train and evaluate the model.

---

# Project Workflow

1. Load dataset
2. Apply image transformations
3. Create DataLoaders
4. Load pretrained ResNet18 model
5. Train the model
6. Validate model performance
7. Evaluate accuracy

---

# Future Improvements

* Hyperparameter tuning
* Real-time webcam emotion detection
* Deployment using Flask or Streamlit
* Testing with larger datasets
* Model optimization for faster inference

---

# Author

Ekansh Makhija
