# Potato Leaf Disease Classification using CNN

## Project Overview

Plant diseases significantly affect agricultural productivity worldwide. Early detection of plant diseases helps farmers take timely action and reduce crop losses.

This project builds a **deep learning model using Convolutional Neural Networks (CNNs)** to automatically classify potato leaf images into different disease categories. The model analyzes images of potato leaves and predicts whether the plant is healthy or affected by a disease.

The goal of this project is to demonstrate an **end-to-end machine learning pipeline**, including data preprocessing, model training, evaluation, and prediction.

---

## Problem Statement

Manual detection of plant diseases requires expertise and can be time-consuming for farmers. By leveraging computer vision and deep learning, we can build an automated system capable of identifying diseases directly from leaf images.

This project focuses on detecting the following potato leaf conditions:

* Early Blight
* Late Blight
* Healthy Leaves

---

## Dataset

The model is trained on images from the **PlantVillage dataset**, which contains labeled images of healthy and diseased plant leaves.

Dataset characteristics:

* Thousands of labeled plant leaf images
* Multiple plant species and diseases
* High-quality images suitable for training computer vision models

For this project, only the **potato leaf subset** was used.

Classes included:

1. Potato Early Blight
2. Potato Late Blight
3. Potato Healthy

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

---

## Project Workflow

The project follows a typical machine learning pipeline:

### 1. Data Exploration

* Loading the dataset
* Checking class distribution
* Visualizing sample images

### 2. Data Preprocessing

* Image resizing
* Normalization
* Dataset splitting (training and validation)

### 3. Model Development

A Convolutional Neural Network (CNN) was built to learn visual features such as:

* leaf textures
* disease spots
* discoloration patterns

The model includes:

* Convolutional layers
* Max pooling layers
* Dense layers
* Dropout for regularization

### 4. Model Training

The model was trained on the training dataset and evaluated using validation data.

Key training parameters include:

* Adam optimizer
* Sparse categorical crossentropy loss
* Accuracy as the evaluation metric

### 5. Model Evaluation

The trained model was evaluated using:

* Accuracy
* Validation loss
* Prediction testing on unseen images

---

## Model Architecture (Summary)

The CNN architecture consists of:

* Convolutional layers for feature extraction
* Max pooling layers for dimensionality reduction
* Fully connected layers for classification
* Softmax output layer for multi-class prediction

---

## Results

The trained CNN achieved high classification accuracy on the validation dataset, demonstrating the effectiveness of deep learning in plant disease detection.

Example predictions include correctly identifying:

* Early Blight infected leaves
* Late Blight infected leaves
* Healthy potato leaves

---

## Repository Structure

Current structure:

```
potato-disease-classification
│
├── notebooks
│   └── potato_disease_classification.ipynb
│
└── README.md
```

Future structure (planned):

```
potato-disease-classification
│
├── data
├── notebooks
├── models
├── src
├── app
└── README.md
```

---

## Future Improvements

Planned improvements for the project include:

* Using **transfer learning models** for improved accuracy
* Deploying the model as a **web application**
* Creating an interface where users can upload leaf images
* Building a mobile-friendly version for farmers

---

## Potential Applications

This system could be used for:

* Early detection of potato diseases
* Agricultural advisory tools
* Smart farming systems
* Mobile disease detection apps for farmers

---

## Author

**Esther Mamai**

Electronic and Computer Engineering Graduate
Machine Learning & Software Engineering Enthusiast

GitHub: https://github.com/EstherMamai
LinkedIn: Esther Mamai

---

## License

This project is for educational and research purposes.
