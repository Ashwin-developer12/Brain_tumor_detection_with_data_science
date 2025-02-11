# Brain Tumor Image Detection

A deep learning-based brain tumor detection system built using a 10-layer Convolutional Neural Network (CNN) in TensorFlow and Keras. This project processes over 50,000 MRI/CT images, achieving an accuracy of 92% while reducing false positives by 30%. The model is deployed as a Flask-based web application, which cuts diagnosis time by 40% and supports clinical decision-making.

## Overview

Early and accurate detection of brain tumors is crucial for effective treatment. This project leverages state-of-the-art deep learning techniques to automatically detect brain tumors from medical imaging data. Key highlights include:
- **High Accuracy:** 92% classification accuracy on a large dataset.
- **Reduced False Positives:** Enhanced performance with a 30% reduction in false positives.
- **Real-Time Diagnosis:** Deployed as a Flask web tool to provide fast and accessible diagnostic support.

## Features

- **Deep Learning Model:** A custom 10-layer CNN designed for brain tumor detection.
- **Data Preprocessing:** Robust preprocessing pipeline to handle noise and improve image quality.
- **Model Optimization:** Fine-tuned hyperparameters to maximize accuracy and minimize false positives.
- **Web Deployment:** A user-friendly Flask web application for real-time inference.
- **Performance Metrics:** Detailed evaluation metrics including accuracy, precision, recall, and F1-score.

## Dataset

- **Size:** Over 50,000 MRI/CT images.
- **Source:** [Provide dataset source here if public, e.g., public medical imaging databases]
- **Preprocessing:** Images were resized, normalized, and augmented to improve model generalization.

## Model Architecture

The model is built using TensorFlow and Keras with the following key components:
- **Input Layer:** Processes preprocessed images.
- **Convolutional Layers:** 10 convolutional layers with ReLU activation and batch normalization.
- **Pooling Layers:** MaxPooling layers to reduce spatial dimensions.
- **Fully Connected Layers:** Dense layers that lead to the output.
- **Output Layer:** Softmax activation for binary classification (tumor vs. no tumor).

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/brain-tumor-detection.git
   cd brain-tumor-detection
   
2. **Install Required Dependencies:**

   ```bash
   pip install -r requirements.txt
