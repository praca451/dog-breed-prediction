# 📌 Project Overview

This project applies Transfer Learning using TensorFlow to classify images of 120 different dog breeds based on a dataset of 10,222 images. The goal is to develop an image classification model that accurately identifies the breed of a dog given an image input.

The model utilizes pre-trained deep learning architectures MobileNetV2.

# 📝 Dataset

The dataset consists of 10,222 labeled images of 120 dog breeds.

The images are sourced from the Kaggle Dog Breed Identification dataset.

The dataset is split into training (80%) and validation (20%) sets for model training and evaluation.

# 🎯 Problem Statement

Given an image of a dog, the model predicts one of 120 possible dog breeds. The project applies Transfer Learning to leverage the power of pre-trained deep learning models, reducing training time and improving accuracy.

# 🏆 Model Outputs

Input: Image of a dog.

Output: Predicted breed of the dog with probability scores for each class.


# 🚀 Technologies Used

TensorFlow & Keras – Deep Learning Framework

Transfer Learning – Pre-trained model (MobileNetV2)

OpenCV & Matplotlib – Image Processing & Visualization

scikit-learn & Pandas – Data Preprocessing

Google Colab & Jupyter Notebook – Model Training & Experimentation


# 🚀 How to Run the Project

1️⃣ Clone the repository

```bash
git clone https://github.com/praca451/dog-breed-prediction.git
cd dog-breed-classification

2️⃣ Install dependencies

```bash
pip install -r requirements.txt

3️⃣ Run the Jupyter Notebook

```bash
jupyter notebook notebooks/dog_breed_classification.ipynb



