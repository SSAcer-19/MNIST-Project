🧠 Handwritten Digit Recognition using TensorFlow

This project implements a deep learning model to classify handwritten digits (0–9) using the MNIST dataset. The model is built and trained using TensorFlow (Keras API).

📌 Project Overview

The MNIST dataset contains:

70,000 grayscale images

28 × 28 pixel resolution

10 digit classes (0–9)

The objective of this project is to build a neural network capable of accurately recognizing handwritten digits.

🚀 Features

Data preprocessing and normalization

Train-test dataset split

Neural network model using TensorFlow

Model training and evaluation

Accuracy and loss visualization

Digit prediction on test samples

🛠️ Tech Stack

Python

TensorFlow (Keras API)

NumPy

Matplotlib

🏗️ Model Architecture

Input Layer (28×28 images)

Flatten / Conv2D Layer

Hidden Dense Layers (ReLU activation)

Output Layer (Softmax – 10 classes)

Optimizer: Adam

Loss Function: Sparse Categorical Crossentropy

Evaluation Metric: Accuracy

📊 Results

Achieved high accuracy (~98–99% on test dataset)

Low validation loss

Correct classification of most handwritten digits

▶️ How to Run

Clone the repository

git clone https://github.com/your-username/repository-name.git

Install dependencies

pip install -r requirements.txt

Run the training script

python train.py
