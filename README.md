# 🧠 Deep Learning Lab Experiments

A comprehensive collection of deep learning experiments covering fundamental concepts to advanced architectures including CNNs, Object Detection, Image Segmentation, Autoencoders, VAEs, and GANs.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Experiments](#experiments)
- [Dataset Links](#dataset-links)
- [Directory Structure](#directory-structure)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Overview

This repository contains 14 comprehensive deep learning experiments implemented as part of the Deep Learning Lab curriculum. Each experiment focuses on a specific concept, ranging from basic neural network components to state-of-the-art generative models.

**Key Topics Covered**
- TensorFlow, Keras, PyTorch
- Neural Networks
- CNNs
- Transfer Learning
- Object Detection (R-CNN, Faster R-CNN)
- Image Segmentation (U-Net)
- Autoencoders & VAEs
- GANs

---

## 🔧 Prerequisites

- Python 3.8+
- CUDA-supported GPU (recommended)
- Basic understanding of ML & Python

---

## 📦 Installation

```bash
# Clone repository
git clone <repository-url>
cd DL_LAB

# Create virtual environment
python -m venv venv
source venv/bin/activate       # Windows: venv\Scripts\activate

# Install dependencies
pip install tensorflow keras torch torchvision numpy pandas matplotlib scikit-learn opencv-python pillow
🧪 Experiments
Experiment 1 — Introduction to Deep Learning Frameworks
Aim: Compare TensorFlow, Keras, PyTorch using a linear regression task.
Files: Ex1.ipynb
Concepts: Basic NN, framework comparison

Experiment 2 — Neural Network Components from Scratch
Aim: Implement neurons, activation functions, backprop for AND, XOR, and Iris dataset.
Files: EX 2.ipynb, Iris.csv
Dataset: Google Drive Link

Experiment 3 — DL Framework for Classification
Aim: Fashion-MNIST classification using Keras.
Files: Ex 3.ipynb, dataset CSV files
Dataset: Google Drive Link

Experiment 4 — Transfer Learning (ResNet50)
Aim: Cats vs Dogs binary classification.
Files: Ex 4.ipynb, images folder
Dataset: Google Drive Link

Experiment 5 — Training Deep Networks
Aim: MNIST training with SGD, Adam, RMSProp.
Files: Ex 5.ipynb
Dataset: Google Drive Link

Experiment 6 — MLP on Fashion-MNIST
Aim: Fully connected classifier with dropout & batch norm.
Files: Ex6.ipynb
Dataset: Google Drive Link

Experiment 7 — CNN Architecture & Feature Visualization
Aim: Visualize convolutions, pooling, feature maps.
Files: Exp7.ipynb
Dataset: Google Drive Link

Experiment 8 — CNN with Data Augmentation
Aim: Makeup vs No-Makeup classification.
Files: Exp8.ipynb
Dataset: Google Drive Link

Experiment 9 — Advanced CNN Tutorial
Aim: Deeper CNN architectures and performance optimization.
Files: convolutional-neural-network-cnn-tutorial.ipynb
Dataset: Google Drive Link

Experiment 10 — Object Detection (Faster R-CNN)
Aim: Object detection on Pascal VOC.
Files: Exp10_FasterRCNN_ObjectDetection.ipynb
Dataset: Google Drive Link

Experiment 11 — Image Segmentation (U-Net)
Aim: Semantic segmentation using U-Net.
Files: unet_segmentation.ipynb, best_unet_model.pth
Dataset: Google Drive Link

Experiment 12 — Autoencoders (CelebA)
Aim: Image reconstruction and compression.
Files: Pre_process.ipynb, model.py, outputs
Dataset: Google Drive Link

Experiment 13 — Variational Autoencoders (VAE)
Aim: Generative modeling on Fashion-MNIST.
Files: model.py, outputs
Dataset: Google Drive Link

Experiment 14 — GANs (Generative Adversarial Networks)
Aim: Generate synthetic images using GAN.
Files: model.py
Dataset: Google Drive Link

📊 Dataset Links
Experiment	Dataset Link	Description
Exp 2	Drive Link	Iris
Exp 3	Drive Link	Fashion-MNIST
Exp 4	Drive Link	Cats vs Dogs
Exp 5	Drive Link	Fashion-MNIST
Exp 6	Drive Link	Fashion-MNIST
Exp 7	Drive Link	Fashion-MNIST
Exp 8	Drive Link	Makeup Dataset
Exp 9	Drive Link	CNN Dataset
Exp 10	Drive Link	Pascal VOC
Exp 11	Drive Link	Segmentation Dataset
Exp 12	Drive Link	CelebA
Exp 13	Drive Link	Fashion-MNIST
Exp 14	Drive Link	GAN Dataset

📁 Directory Structure
go
Copy code
DL_LAB/
├── Exp_1/
│   └── Ex1.ipynb
├── Exp_2/
│   ├── EX 2.ipynb
│   └── Iris.csv
├── Exp_3/
│   ├── Ex 3.ipynb
│   ├── fashion-mnist_train.csv
│   ├── fashion-mnist_test.csv
│   └── idx-ubyte files
├── Exp_4/
│   ├── Ex 4.ipynb
│   ├── cats_set/
│   └── dogs_set/
├── Exp_5/
│   └── Ex 5.ipynb
├── Exp_6/
│   └── Ex6.ipynb
├── Exp_7/
│   └── Exp7.ipynb
├── Exp_8/
│   └── Exp8.ipynb
├── Exp_9/
│   └── convolutional-neural-network-cnn-tutorial.ipynb
├── Exp_10/
│   └── Exp10_FasterRCNN_ObjectDetection.ipynb
├── Exp_11/
│   └── unet_segmentation.ipynb
├── Exp_12/
│   └── Pre_process.ipynb
├── Exp_13/
│   └── model.py
├── Exp_14/
│   └── model.py
└── README.md
🚀 Usage
Running an Experiment
bash
Copy code
cd Exp_1
jupyter notebook Ex1.ipynb
Each notebook contains:

Data loading

Preprocessing

Model architecture

Training loop

Evaluation

Visualization

🛠️ Technologies Used
TensorFlow, Keras, PyTorch

NumPy, Pandas, Matplotlib, Scikit-learn

CNNs, ResNet50, U-Net

Autoencoders, VAE, GAN

📈 Results
Outputs include:

Accuracy/loss curves

Confusion matrices

ROC curves

Feature maps

Segmentations

Reconstructions

Generated samples

See experiment folders for visualizations.

🤝 Contributing
Pull requests are welcome. Open an issue before major changes.

📄 License
MIT License. See LICENSE.

👤 Author
Your Name
GitHub: @yourusername

📝 Notes
Ensure sufficient GPU memory for Exp 10–14.

Download datasets before running notebooks.

Some models take hours to train.

Last Updated: November 2025
Status: ✅ All experiments completed

yaml
Copy code

---

If you want, I can **convert this into a perfectly structured GitHub Pages website**, or generate **