# Neural-Networks | UFES-2025/2 | CNN's Lung-Disease

# Lung Disease Classification with Convolutional Neural Networks

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Computer Vision](https://img.shields.io/badge/Topic-Computer%20Vision-purple)
![Status](https://img.shields.io/badge/Status-Academic%20Project-lightgrey)

This repository contains a **Convolutional Neural Network (CNN)** implementation for **lung disease image classification**, developed as part of a **Neural Networks coursework assignment**.

The project explores the use of **deep learning and computer vision techniques** to classify lung images using **PyTorch**, including both a **custom CNN architecture** and **transfer learning with a pretrained model**.

---

# Objective

The main goal of this project is to develop and train a **Convolutional Neural Network** capable of classifying lung images into disease categories.

The project includes:

- Image preprocessing
- Dataset construction
- CNN model implementation
- Model training and validation
- Transfer learning using a pretrained network

This workflow reflects common practices in **medical image analysis using deep learning**.

---

# Project Workflow

The notebook follows a structured pipeline for building and training deep learning models.

## 1. Data Acquisition

The dataset is downloaded and prepared for training.

Key steps include:

- Downloading lung image data
- Inspecting image samples
- Organizing the dataset structure

---

## 2. Image Preprocessing

Images are prepared before being fed into the neural network.

Preprocessing steps include:

- Loading images in different formats
- Ensuring images have **three color channels**
- Converting images to **PyTorch tensors**
- Rescaling values to **8-bit range**
- Applying dataset **transformations**

Typical transformations may include:

- Normalization
- Resizing
- Data augmentation (when applicable)

---

## 3. Dataset Construction

A dataset class is created to handle:

- Image loading
- Transform application
- Label retrieval

This dataset is used with **PyTorch DataLoader** to enable efficient batch training.

---

# Model Architecture

## Custom Convolutional Neural Network

A CNN architecture is implemented from scratch using PyTorch.

Typical components include:

- Convolutional layers
- Activation functions (ReLU)
- Pooling layers
- Fully connected layers
- Output classification layer

The CNN learns hierarchical features directly from lung images.

---

## Transfer Learning (Pretrained Model)

In addition to the custom CNN, the project explores **transfer learning** using a pretrained model.

Steps include:

- Loading a pretrained network (e.g., ImageNet-trained model)
- Freezing feature extraction layers
- Training only the **classification layer**

This approach allows faster convergence and often improves performance when datasets are limited.

---

# Training Process

The training pipeline includes:

- Forward propagation
- Loss computation
- Backpropagation
- Weight updates using an optimizer

Performance is monitored using:

- Training loss
- Validation metrics

---

# Validation

Model performance is evaluated using a **validation set**.

The validation step ensures that the model:

- Generalizes to unseen data
- Avoids overfitting
- Improves over training epochs

---

# Technologies Used

- **Python**
- **PyTorch**
- **NumPy**
- **Jupyter Notebook**

---

# How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```
2. Navigate to the project folder
```bash
cd your-repository
```
3. Open the notebook
```bash
jupyter notebook
```
or
```bash
jupyter lab
```
4. Run the cells sequentially.

---

# Author
Marcus Louriçal Neves Filho
Computer Science Undergraduate
Federal University of Espírito Santo (UFES)
