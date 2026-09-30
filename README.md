# Breast Cancer Classification Using Neural Network

## Project Overview

This project uses a simple Neural Network to classify breast cancer tumor data into two classes:

- Malignant
- Benign

The project was developed using Python, Scikit-learn, TensorFlow/Keras, and Google Colab.

## Objective

The main objective is to build and evaluate a Neural Network model that can classify breast cancer data into malignant or benign categories.

## Dataset

The project uses the Breast Cancer dataset available through `sklearn.datasets.load_breast_cancer()`.

Dataset details:

- Total samples: 569
- Features: 30
- Classes: 2
- Malignant: 212
- Benign: 357
- Missing values: None

The labels used in the notebook are:

- `0` = Malignant
- `1` = Benign

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras
- Google Colab

## Methodology

The project follows these steps:

1. Load the breast cancer dataset.
2. Convert the dataset into a Pandas DataFrame.
3. Separate features and target labels.
4. Split the data into training and testing sets.
5. Standardize the feature values using `StandardScaler`.
6. Build a Neural Network using TensorFlow/Keras.
7. Train the model for 10 epochs.
8. Evaluate the model using separate test data.
9. Use the trained model to make a prediction for an individual sample.

## Neural Network Architecture

The model contains:

- Input: 30 features
- Hidden layer: 20 neurons with ReLU activation
- Output layer: 2 neurons with Sigmoid activation
- Optimizer: Adam
- Loss function: Sparse Categorical Crossentropy
- Training: 10 epochs

## Train-Test Split

The dataset was divided into:

- Training data: 80%
- Testing data: 20%

The resulting data sizes were:

- Training samples: 455
- Testing samples: 114

## Results

The model achieved:

**Test Accuracy: 96.49%**

The model was evaluated using data that was kept separate from the training process.

## Prediction Example

The notebook also demonstrates prediction for an individual sample.

The model predicted:

**Benign**

## Project Files

- `Breast_Cancer_Classification_with_Neural_Network (1).ipynb` — Jupyter Notebook containing the complete project.
- `Breast-Cancer-Classification-Using-Neural-Network.pptx` — Project presentation.
- `README.md` — Project documentation.

## How to Run

1. Open the `.ipynb` file using Google Colab or Jupyter Notebook.
2. Run the notebook cells in order.
3. The required Python libraries are imported in the notebook.
4. Run the training and evaluation sections to reproduce the results.

## Disclaimer

This project is developed for educational and internship purposes. It is a machine-learning classification project and is **not a medical diagnostic system**.
