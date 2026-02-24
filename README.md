Classification of Dry Beans with Neural Network

A computer vision and machine learning project that builds a neural network classifier to identify dry bean species based on physical measurements. This repository implements a neural network model using TensorFlow/Keras and evaluates its performance on a labeled dry beans dataset. 

🧠 Project Summary

This project uses a dataset of dry bean measurements (e.g., area, perimeter, shape, texture metrics) to train a neural network classifier that predicts the species of bean. The model distinguishes between 7 distinct bean types using supervised learning.

The dataset includes features extracted from bean images, and the neural network learns patterns to classify each sample into its corresponding species.

📁 Repository Structure

├── Dry Beans Neural Network.ipynb         # Main Jupyter Notebook

├── beans_dataset.csv                      # Dataset of 7 bean species

├── README.md                              # Project documentation

└── (Optional) requirements.txt            # Python package dependencies

📦 Technologies & Libraries

The project uses:

Python

TensorFlow & Keras – Neural network modeling

NumPy & Pandas – Data processing

scikit‑learn – Data splitting and preprocessing

Matplotlib / Seaborn – Data visualization

🔍 How the Model Works

The notebook demonstrates the full pipeline:

Data Loading
Read the bean dataset from beans_dataset.csv.

Exploratory Data Analysis (EDA)
Inspect data distribution and class balance.

Preprocessing

Encode class labels.

Normalize feature values.

Split into training and testing sets.

Neural Network Model

Build a multi‑layer neural network using Keras.

Use softmax activation at the output layer for multi‑class prediction.

Training & Evaluation

Train the model on the training set.

Evaluate accuracy on the test set.

Visualize training metrics (loss/accuracy curves).

Predictions

Use the trained model to classify unseen bean samples.

📊 What You’ll Learn

How to preprocess real‑world tabular data for machine learning

How to build and train a neural network classifier in TensorFlow/Keras

How to evaluate classification models using a confusion matrix and accuracy metric

How feature scaling and label encoding affect model performance

📈 Results and Performance

The notebook includes:

Accuracy and loss curves

Confusion matrix for multi‑class evaluation

Examples of predicted vs. actual bean species
