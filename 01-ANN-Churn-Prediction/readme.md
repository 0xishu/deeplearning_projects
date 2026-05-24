# Customer Churn Prediction using Deep Learning

## Overview

This project predicts customer churn using an Artificial Neural Network (ANN).
The model is trained on banking customer data to determine whether a customer is likely to leave the bank based on various customer attributes.

Customer churn prediction helps businesses identify customers at risk of leaving, allowing companies to improve customer retention strategies.

---

## Features

* Data preprocessing and cleaning
* Feature encoding and scaling
* Artificial Neural Network (ANN) implementation
* Model training and evaluation
* Confusion matrix visualization
* Accuracy analysis

---

## Technologies Used

* Python
* TensorFlow / Keras
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## Dataset Information

The dataset contains banking customer information such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Credit Card Status
* Active Member Status
* Estimated Salary

Target Variable:

* Exited (1 = Customer Left, 0 = Customer Stayed)

---

## Project Structure

```bash
customer-churn-prediction/
│
├── data/
│   └── churn.csv
│
├── notebooks/
│   └── churn-modelling.ipynb
│
├── images/
│   ├── confusion_matrix.png
│   └── accuracy_plot.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Model Architecture

The Artificial Neural Network consists of:

* Input Layer
* Hidden Dense Layers
* ReLU Activation Function
* Sigmoid Output Layer

The model is trained using binary classification techniques to predict customer churn.

---

## Results

The model successfully predicts customer churn with good classification performance.

Evaluation metrics used:

* Accuracy Score
* Confusion Matrix
* Loss Analysis

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
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
churn-modelling.ipynb
```

---

## Future Improvements

* Hyperparameter tuning
* Model deployment using Streamlit
* Better feature engineering
* Real-time churn prediction system
* Comparison with other ML models

---

## Author

Priyanshu Panigrahi

Deep Learning & Machine Learning Enthusiast

