# MNIST Digit Classification using CNN

## Project Overview
This project implements a Convolutional Neural Network (CNN) model to classify handwritten digits (0–9) using the MNIST dataset. The model is built using TensorFlow and Keras and achieves high classification accuracy.

## Dataset
Dataset used: MNIST in CSV format from Kaggle

Dataset Link:  
:contentReference[oaicite:0]{index=0}

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib

## Model Architecture
The CNN model consists of:
- Convolutional (Conv2D) layers
- MaxPooling layers
- Flatten layer
- Dense layers
- Softmax output layer

## Results
- Training Accuracy: ~98.87%
- Test Accuracy: ~99.01%
- Test Loss: ~0.0397

## Features
- Image preprocessing
- CNN-based image classification
- Model training and evaluation
- Accuracy and loss visualization

## How to Run
1. Clone the repository
2. Install the required libraries
3. Open the notebook
4. Run all cells
5. Ensure the dataset file is available in the project folder

## Project Structure
```text
MNIST-CNN-Project/
│
├── mnist_cnn.ipynb
├── README.md
├── requirements.txt
