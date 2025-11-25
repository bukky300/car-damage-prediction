# 🚗🔍 Car Damage Classification System

A deep learning pipeline that detects and classifies car damage severity from images. Built with PyTorch, ResNet, Optuna, FastAPI, and Streamlit. Designed for real-world deployment and scalability.

<img width="824" height="977" alt="image" src="https://github.com/user-attachments/assets/c0384884-62a3-4613-bce5-dbc91a71c774" />


# 🧠 Objective

The aim was to build a reliable system that identifies the level of car damage from vehicle images.
The final product includes:

A trained deep learning model (ResNet)

Hyperparameter tuning using Optuna

A FastAPI inference server

A Streamlit web app for easy interaction

 Evaluation

This showcases end-to-end deep learning engineering — from data to deployment.

#### 📦 Dataset

Image dataset containing multiple classes of car damage. Preprocessing included:

Resizing

Normalization

Augmentations for robustness

Train/validation split

🤖 Models Trained

I experimented with several CNN architectures to compare performance:

# 🏗️ Models

Custom CNN

EfficientNet-B0

ResNet (best performer)


🔧 Tools & Libraries

PyTorch

Torchvision

Optuna for hyperparameter optimization

Matplotlib + Seaborn for metrics

FastAPI

Streamlit

scikit-learn for metrics and reports

#### Hyperparameter Tuning (Optuna)

Optuna optimized:

Learning rate

Batch size


This cut training time and boosted accuracy.

# 🏆 Best Model: ResNet

ResNet delivered the strongest combination of accuracy, generalization, and training stability.


# 🖥️ Deployment
⚡ FastAPI

A live inference server that accepts uploaded images and returns predictions in real time.

🌐 Streamlit App

Interactive UI where users can:

Upload car images

See model predictions

Great for demos and recruiters.

🔍 Key Features

End-to-end deep learning workflow

Model comparison across architectures

Optuna-based optimization

Production-ready API

Web UI for real-time inference

# 🧰 Tech Stack

Python

PyTorch, Torchvision

Optuna

FastAPI

Streamlit

scikit-learn

Matplotlib, Seaborn

Pillow
