🌾 AI-Powered Crop Yield Prediction and Optimization
📌 Overview

This project uses Artificial Intelligence (AI) and Deep Learning (CNN) to predict the condition of crops based on images.
It helps farmers and researchers identify healthy crops, unhealthy crops, weeds, and dry soil — along with suggestions for better crop management.

🎯 Objective

To develop an AI model that can:

Classify crop images into four categories.

Provide instant suggestions to improve or maintain crop health.

Offer a simple web-based interface using Gradio for real-time prediction.

🧠 Concept

The model is built using a Convolutional Neural Network (CNN) trained with TensorFlow and Keras.
It analyzes image features like color, texture, and shape to classify crop conditions accurately.

📂 Dataset

The dataset contains 4 folders, each with 10 sample images:

dataset/
 ├── healthy_crop/
 ├── unhealthy_crop/
 ├── weeds/
 └── dry_soil/


Each folder represents one label used to train the model.

⚙️ Tech Stack

Python

TensorFlow / Keras

Gradio

NumPy

Google Colab

🚀 How to Run

Open the project in Google Colab.

Upload your dataset folder (with the 4 subfolders).

Run the training cells to train the CNN model.

Run the Gradio section to deploy the model as a web app.

Upload a crop image to test predictions.

🖥️ Web App Features

Upload any crop image.

Get instant prediction: Healthy, Unhealthy, Weed, or Dry.

Receive actionable suggestions:

Healthy: Maintain current care routine.

Unhealthy: Check for pests or nutrients.

Weed: Remove weeds promptly.

Dry: Increase irrigation.

📊 Results

The model achieved good validation accuracy with limited data.

It demonstrates how AI can support smart and sustainable farming.

💡 Future Scope

Train the model with a larger dataset for higher accuracy.

Add more crop types and soil conditions.

Integrate with mobile apps for real-time field use.
