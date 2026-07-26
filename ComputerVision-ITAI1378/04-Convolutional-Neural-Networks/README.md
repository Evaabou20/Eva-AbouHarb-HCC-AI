# Convolutional Neural Networks

## Project Overview

This project explores convolutional neural networks (CNNs) for image classification using PyTorch. Building upon the previous neural network project, I designed, trained, and evaluated a CNN capable of distinguishing between Chihuahua dogs and muffins. The project demonstrates how convolutional layers automatically learn visual features, resulting in higher performance than a traditional fully connected neural network.

This project was completed as part of **ITAI 1378 – Computer Vision** at **Houston City College**.

---

## Objectives

- Understand the architecture of convolutional neural networks.
- Build a CNN for binary image classification.
- Apply image preprocessing and data augmentation techniques.
- Train and evaluate a deep learning model.
- Compare CNN performance with a traditional neural network.

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Google Colab

---

## CNN Architecture

The model consists of:

- Three Convolutional Layers
- ReLU Activation Functions
- Max Pooling Layers
- Fully Connected Layers
- Dropout Regularization
- Softmax Classification

---

## Dataset

**Chihuahua vs. Muffin Dataset**

- 120 training images
- 30 validation images
- Binary image classification

The dataset was divided into separate training and validation sets to evaluate how well the model generalized to unseen images.

---

## Training Configuration

- Optimizer: Adam
- Learning Rate: 0.001
- Loss Function: CrossEntropyLoss
- Epochs: 15
- Image Size: 224 × 224

Data augmentation included:

- Random horizontal flipping
- Random rotation
- Image normalization

---

## Results

The CNN achieved excellent classification performance.

**Training Accuracy:** 97.50%

**Validation Accuracy:** 96.67%

The model successfully learned visual features such as edges, textures, and shapes, allowing it to outperform the traditional neural network developed in the previous module.

---

## Project Files

| File | Description |
|------|-------------|
| `Lab05_CNN_Chihuahua_Muffin.ipynb` | CNN implementation demonstrating data preparation, model architecture, training, evaluation, and prediction visualization. |
| `L05_EvaAbouHarb_ITAI_1378.pdf` | Reflective journal discussing CNN concepts, performance analysis, challenges, ethical considerations, and real-world applications. |

---

## Skills Demonstrated

- Convolutional Neural Networks (CNNs)
- Deep Learning
- Image Classification
- PyTorch
- Data Augmentation
- Model Training
- Model Evaluation
- Computer Vision

---

## Key Learning Outcomes

This project strengthened my understanding of convolutional neural networks and demonstrated why CNNs are the preferred architecture for image classification. I gained practical experience preparing image datasets, designing CNN architectures, training deep learning models with GPU acceleration, evaluating model performance, and interpreting prediction results.

Comparing this model with the previous fully connected neural network highlighted the importance of convolutional layers in automatically learning spatial features such as edges, textures, and shapes, leading to improved classification accuracy.
