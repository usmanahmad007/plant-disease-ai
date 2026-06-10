🌿 Plant Disease Detection using Deep Learning (ResNet18 + PyTorch)
🚀 Overview

This project implements an AI-powered plant disease classification system using deep learning. The model is trained on the PlantVillage dataset and is capable of detecting multiple crop diseases from leaf images.

It uses transfer learning (ResNet18) to achieve high accuracy on multi-class image classification tasks.

🧠 Key Features
Deep Learning-based image classification
15+ plant disease categories
Transfer Learning with ResNet18
Train/Validation split for robust evaluation
Performance metrics (Accuracy, Loss, F1-score)
Confusion Matrix analysis
Training visualization (Loss & Accuracy graphs)
📊 Dataset
Dataset: PlantVillage Dataset
Source: Kaggle / HuggingFace / Kaggle Input
Classes include:
Tomato diseases (Early blight, Late blight, Leaf Mold, etc.)
Potato diseases (Early blight, Late blight, Healthy)
Pepper Bell diseases
Healthy plant categories
🏗️ Model Architecture
Backbone: ResNet18 (Pretrained on ImageNet)
Custom Fully Connected Layer
Loss Function: CrossEntropyLoss
Optimizer: Adam
