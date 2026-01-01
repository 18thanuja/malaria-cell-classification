🦠 Malaria Cell Image Classification using CNN
📌 Project Overview

Malaria is a life-threatening disease caused by parasites transmitted through mosquito bites. Traditional diagnosis through manual microscopic examination is time-consuming and depends heavily on expert technicians.

This project uses Deep Learning (Convolutional Neural Networks – CNN) to automatically classify malaria-infected and uninfected red blood cell images, helping improve diagnostic speed and accuracy.

🎯 Objectives

Automate malaria cell image classification using deep learning

Reduce dependency on manual microscopic diagnosis

Improve accuracy and consistency in medical image analysis

Demonstrate real-world healthcare applications of AI

🧠 Technologies & Tools Used

Programming Language: Python

Deep Learning Framework: TensorFlow / Keras

Libraries: NumPy, Pandas, OpenCV, Matplotlib, Seaborn, Scikit-learn

Dataset: NIH Malaria Cell Images Dataset

Model Type: Convolutional Neural Network (CNN)

📂 Dataset Details

Source: National Institutes of Health (NIH) – Kaggle

Total Images: 27,558

Classes:

Parasitized (Infected)

Uninfected

Image Format: PNG

Image Size: ~100×100 pixels

The dataset is balanced, making it suitable for binary classification tasks.

⚙️ Project Workflow

Data Collection

Download malaria cell images dataset

Data Preprocessing

Image resizing

Normalization

Data augmentation

Model Building

Convolutional layers

MaxPooling layers

Dense layers

Dropout for regularization

Model Training

Binary cross-entropy loss

Adam optimizer

Evaluation

Accuracy

Precision

Recall

F1-score

Prediction

Classifies cell images as Infected or Uninfected

🏗️ CNN Architecture

Conv2D layers for feature extraction

MaxPooling layers for dimensionality reduction

Flatten layer

Fully connected Dense layers

Sigmoid activation for binary classification

📊 Results

Successfully trained CNN model for malaria detection

Achieved high accuracy on validation data

Model demonstrates effective learning of image patterns

Reduced diagnosis time from minutes to seconds

🚀 Key Features

Automated medical image classification

Scalable for real-world healthcare applications

Can be extended to detect other diseases

Suitable for low-resource environments

🧪 Sample Output

Input: Microscopic red blood cell image

Output:

Prediction: Infected / Uninfected

Confidence Score: Model probability
