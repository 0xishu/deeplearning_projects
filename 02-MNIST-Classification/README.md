MNIST Handwritten Digit Classification using Deep Learning

## Overview

This project implements a handwritten digit classification system using an Artificial Neural Network (ANN) built with TensorFlow and Keras.

The model is trained on the MNIST dataset to recognize and classify handwritten digits from 0–9 using deep learning techniques.

This project focuses on understanding:

* Neural Networks
* Image Classification
* Data Normalization
* Model Training and Evaluation
* Deep Learning Workflow using TensorFlow/Keras

---

## Dataset

The project uses the MNIST handwritten digit dataset available directly from Keras datasets.

Dataset Details:

* 60,000 training images
* 10,000 testing images
* Grayscale images of size 28x28
* 10 output classes (digits 0–9)

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn

---

## Project Workflow

1. Load MNIST dataset
2. Normalize image pixel values
3. Build ANN model using Keras Sequential API
4. Train the neural network
5. Evaluate model performance
6. Visualize training accuracy and loss
7. Predict handwritten digits

---

## Model Architecture

The neural network consists of:

* Flatten Layer
* Dense Hidden Layer (128 neurons, ReLU)
* Dense Hidden Layer (32 neurons, ReLU)
* Output Layer (10 neurons, Softmax)

---

## Results

The model achieves strong classification accuracy on handwritten digit recognition.

Evaluation Metrics:

* Accuracy Score
* Training Loss
* Validation Loss
* Training Accuracy
* Validation Accuracy

---

## Visualizations

The project includes:

* Sample digit visualization
* Accuracy graph
* Loss graph
* Prediction testing

---

## Installation

Clone the repository:

```bash
git clone https://github.com/0xishu/deeplearning_projects.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
jupyter notebook
```

Open:

```bash
mnist_classification.ipynb
```

---

## Future Improvements

* Implement CNN-based digit classification
* Improve model accuracy
* Add confusion matrix visualization
* Deploy model using Streamlit
* Real-time digit recognition interface

---

## Author

Priyanshu Panigrahi

Deep Learning & AI Enthusiast
