# 🖼️ CIFAR-10 Object Recognition Using ResNet50

A Deep Learning project for **multi-class image classification** using the **CIFAR-10 dataset** and a **ResNet50-based transfer learning model**.

The project loads and preprocesses 50,000 CIFAR-10 training images, converts the class labels into numerical form, splits the data into training and testing sets, scales the images, and trains a ResNet50-based classification model to recognize objects belonging to 10 different classes.

---

## 📌 Project Overview

Image classification is a fundamental Computer Vision task where a Deep Learning model learns to identify the object present in an image.

In this project, the **CIFAR-10 dataset** is used to classify images into 10 object categories.

The project implements two approaches:

1. A basic Neural Network
2. A **ResNet50-based transfer learning model**

The ResNet50 model significantly improves the classification performance compared with the basic Neural Network.

The notebook is configured to run with a **GPU accelerator** in Google Colab. 

---

## 🎯 Objectives

- Download the CIFAR-10 dataset using Kaggle.
- Extract and process the image dataset.
- Load and process image labels.
- Convert categorical labels into numerical values.
- Convert images into NumPy arrays.
- Explore sample images.
- Split the dataset into training and testing sets.
- Normalize image pixel values.
- Build a basic Neural Network for comparison.
- Implement a pretrained ResNet50 model.
- Apply transfer learning for CIFAR-10 classification.
- Train the model for 10 epochs.
- Evaluate the model on test data.
- Visualize training and validation loss.
- Visualize training and validation accuracy.

---

## 📊 Dataset

The project uses the **CIFAR-10 dataset**.

The dataset contains:

- **50,000 training images**
- **32 × 32 RGB images**
- **10 object classes**
- **5,000 images per class**

The notebook loads the training labels from:

```text
trainLabels.csv
