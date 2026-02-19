🍎 Rotten Fruits & Vegetables Detection using Transfer Learning
👩‍💻 Developed by: Lahari Boyina
📌 Project Overview

This project focuses on detecting whether fruits and vegetables are fresh or rotten using Transfer Learning with Convolutional Neural Networks (CNNs).

Instead of training a deep learning model from scratch, a pre-trained CNN architecture is leveraged to improve classification accuracy and reduce training time, especially with a limited dataset.

The system can assist in:

Automated food quality inspection

Smart agriculture solutions

Supply chain quality control

🎯 Objectives

Classify fruits and vegetables as Fresh or Rotten

Apply Transfer Learning to improve performance

Reduce overfitting using data augmentation

Evaluate model performance using accuracy and loss metrics

🧠 Model Architecture

Used a pre-trained CNN model (e.g., MobileNet / VGG16)

Removed top classification layers

Added custom Dense layers

Applied Dropout for regularization

Fine-tuned upper layers for better feature adaptation

🔁 Why Transfer Learning?

Training deep neural networks from scratch requires large datasets and high computational power. Transfer Learning allows:

Faster training

Higher accuracy with limited data

Better generalization

🛠 Technologies Used

Python

TensorFlow / Keras

Convolutional Neural Networks (CNN)

Transfer Learning

NumPy

Matplotlib

OpenCV

📊 Training & Evaluation

Image preprocessing and resizing

Data augmentation (rotation, zoom, flipping)

Model training with validation split

Performance monitoring using:

Accuracy

Loss curves

Confusion Matrix (if implemented)

📂 Project Structure

Rotten-Fruits-Detection/
│
├── dataset/
├── models/
├── notebooks/
├── train.py
├── evaluate.py
├── requirements.txt
└── README.md

