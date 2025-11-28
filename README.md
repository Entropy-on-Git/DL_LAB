# 🧠 Deep Learning Lab Experiments

<div align="center">

![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Lab-blue?style=for-the-badge&logo=tensorflow)
![Python](https://img.shields.io/badge/Python-3.8+-green?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

**A comprehensive collection of deep learning experiments covering fundamental concepts to advanced architectures**

[Overview](#-overview) • [Installation](#-installation) • [Experiments](#-experiments) • [Datasets](#-dataset-links) • [Results](#-results)

</div>

---

## 📋 Table of Contents

- [🎯 Overview](#-overview)
- [🔧 Prerequisites](#-prerequisites)
- [📦 Installation](#-installation)
- [🧪 Experiments](#-experiments)
- [📊 Dataset Links](#-dataset-links)
- [📁 Directory Structure](#-directory-structure)
- [🚀 Usage](#-usage)
- [🛠️ Technologies Used](#️-technologies-used)
- [📈 Results](#-results)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🎯 Overview

This repository contains **14 comprehensive deep learning experiments** implemented as part of the Deep Learning Lab curriculum. Each experiment focuses on a specific concept, ranging from basic neural network components to state-of-the-art generative models.

### 🌟 Key Topics Covered

<table>
<tr>
<td width="50%">

- ✅ TensorFlow, Keras, PyTorch
- ✅ Neural Networks from Scratch
- ✅ Convolutional Neural Networks
- ✅ Transfer Learning (ResNet50)

</td>
<td width="50%">

- ✅ Object Detection (R-CNN, Faster R-CNN)
- ✅ Image Segmentation (U-Net)
- ✅ Autoencoders & VAEs
- ✅ Generative Adversarial Networks

</td>
</tr>
</table>

---

## 🔧 Prerequisites

```
✓ Python 3.8 or higher
✓ CUDA-supported GPU (recommended for training)
✓ Basic understanding of Machine Learning
✓ Familiarity with Python programming
```

---

## 📦 Installation

### Step 1: Clone the Repository

```bash
git clone <repository-url>
cd DL_LAB
```

### Step 2: Create Virtual Environment

```bash
# Create virtual environment
python -m venv venv

# Activate (Linux/Mac)
source venv/bin/activate

# Activate (Windows)
venv\Scripts\activate
```

### Step 3: Install Dependencies

```bash
pip install tensorflow keras torch torchvision numpy pandas matplotlib scikit-learn opencv-python pillow jupyter
```

---

## 🧪 Experiments

### 🔹 Experiment 1 — Introduction to Deep Learning Frameworks

> **Aim:** Compare TensorFlow, Keras, and PyTorch using a linear regression task

- **Files:** `Ex1.ipynb`
- **Concepts:** Basic Neural Networks, Framework Comparison
- **Difficulty:** ⭐ Beginner

---

### 🔹 Experiment 2 — Neural Network Components from Scratch

> **Aim:** Implement neurons, activation functions, and backpropagation for AND, XOR, and Iris dataset

- **Files:** `EX 2.ipynb`, `Iris.csv`
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Perceptrons, Activation Functions, Gradient Descent
- **Difficulty:** ⭐⭐ Intermediate

---

### 🔹 Experiment 3 — DL Framework for Classification

> **Aim:** Fashion-MNIST classification using Keras

- **Files:** `Ex 3.ipynb`, CSV dataset files
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Multi-class Classification, Softmax
- **Difficulty:** ⭐⭐ Intermediate

---

### 🔹 Experiment 4 — Transfer Learning with ResNet50

> **Aim:** Binary classification of Cats vs Dogs using pre-trained ResNet50

- **Files:** `Ex 4.ipynb`, images folder
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Transfer Learning, Fine-tuning, Feature Extraction
- **Difficulty:** ⭐⭐⭐ Advanced

---

### 🔹 Experiment 5 — Training Deep Networks

> **Aim:** MNIST digit classification comparing SGD, Adam, and RMSProp optimizers

- **Files:** `Ex 5.ipynb`
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Optimization Algorithms, Learning Rate, Convergence
- **Difficulty:** ⭐⭐ Intermediate

---

### 🔹 Experiment 6 — MLP on Fashion-MNIST

> **Aim:** Fully connected classifier with dropout and batch normalization

- **Files:** `Ex6.ipynb`
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Regularization, Dropout, Batch Normalization
- **Difficulty:** ⭐⭐ Intermediate

---

### 🔹 Experiment 7 — CNN Architecture & Feature Visualization

> **Aim:** Visualize convolutions, pooling operations, and feature maps

- **Files:** `Exp7.ipynb`
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Convolution, Pooling, Feature Extraction
- **Difficulty:** ⭐⭐⭐ Advanced

---

### 🔹 Experiment 8 — CNN with Data Augmentation

> **Aim:** Makeup vs No-Makeup classification with augmentation techniques

- **Files:** `Exp8.ipynb`
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Data Augmentation, Image Preprocessing
- **Difficulty:** ⭐⭐ Intermediate

---

### 🔹 Experiment 9 — Advanced CNN Tutorial

> **Aim:** Deeper CNN architectures and performance optimization

- **Files:** `convolutional-neural-network-cnn-tutorial.ipynb`
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Deep CNNs, Architecture Design, Optimization
- **Difficulty:** ⭐⭐⭐ Advanced

---

### 🔹 Experiment 10 — Object Detection with Faster R-CNN

> **Aim:** Object detection on Pascal VOC dataset

- **Files:** `Exp10_FasterRCNN_ObjectDetection.ipynb`
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Region-based CNNs, Bounding Boxes, mAP
- **Difficulty:** ⭐⭐⭐⭐ Expert

---

### 🔹 Experiment 11 — Image Segmentation with U-Net

> **Aim:** Semantic segmentation using U-Net architecture

- **Files:** `unet_segmentation.ipynb`, `best_unet_model.pth`
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Semantic Segmentation, Encoder-Decoder, Skip Connections
- **Difficulty:** ⭐⭐⭐⭐ Expert

---

### 🔹 Experiment 12 — Autoencoders on CelebA

> **Aim:** Image reconstruction and compression using autoencoders

- **Files:** `Pre_process.ipynb`, `model.py`, outputs
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Dimensionality Reduction, Reconstruction Loss
- **Difficulty:** ⭐⭐⭐ Advanced

---

### 🔹 Experiment 13 — Variational Autoencoders (VAE)

> **Aim:** Generative modeling on Fashion-MNIST using VAE

- **Files:** `model.py`, outputs
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Latent Space, KL Divergence, Generative Models
- **Difficulty:** ⭐⭐⭐⭐ Expert

---

### 🔹 Experiment 14 — Generative Adversarial Networks

> **Aim:** Generate synthetic images using GAN architecture

- **Files:** `model.py`
- **Dataset:** [📥 Download](https://drive.google.com/drive/folders/your-link-here)
- **Concepts:** Generator, Discriminator, Adversarial Training
- **Difficulty:** ⭐⭐⭐⭐ Expert

---

## 📊 Dataset Links

| Experiment | Dataset | Description |
|------------|---------|-------------|
| **Exp 2** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | Iris Dataset |
| **Exp 3** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | Fashion-MNIST |
| **Exp 4** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | Cats vs Dogs |
| **Exp 5** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | MNIST Digits |
| **Exp 6** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | Fashion-MNIST |
| **Exp 7** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | Fashion-MNIST |
| **Exp 8** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | Makeup Dataset |
| **Exp 9** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | CNN Dataset |
| **Exp 10** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | Pascal VOC |
| **Exp 11** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | Segmentation Dataset |
| **Exp 12** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | CelebA |
| **Exp 13** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | Fashion-MNIST |
| **Exp 14** | [📥 Download](https://drive.google.com/drive/folders/your-link-here) | GAN Dataset |

---

## 📁 Directory Structure

```
DL_LAB/
│
├── 📂 Exp_1/
│   └── Ex1.ipynb
│
├── 📂 Exp_2/
│   ├── EX 2.ipynb
│   └── Iris.csv
│
├── 📂 Exp_3/
│   ├── Ex 3.ipynb
│   ├── fashion-mnist_train.csv
│   └── fashion-mnist_test.csv
│
├── 📂 Exp_4/
│   ├── Ex 4.ipynb
│   ├── 📁 cats_set/
│   └── 📁 dogs_set/
│
├── 📂 Exp_5/
│   └── Ex 5.ipynb
│
├── 📂 Exp_6/
│   └── Ex6.ipynb
│
├── 📂 Exp_7/
│   └── Exp7.ipynb
│
├── 📂 Exp_8/
│   └── Exp8.ipynb
│
├── 📂 Exp_9/
│   └── convolutional-neural-network-cnn-tutorial.ipynb
│
├── 📂 Exp_10/
│   └── Exp10_FasterRCNN_ObjectDetection.ipynb
│
├── 📂 Exp_11/
│   ├── unet_segmentation.ipynb
│   └── best_unet_model.pth
│
├── 📂 Exp_12/
│   ├── Pre_process.ipynb
│   ├── model.py
│   └── 📁 outputs/
│
├── 📂 Exp_13/
│   ├── model.py
│   └── 📁 outputs/
│
├── 📂 Exp_14/
│   └── model.py
│
└── 📄 README.md
```

---

## 🚀 Usage

### Running an Experiment

```bash
# Navigate to experiment directory
cd Exp_1

# Launch Jupyter Notebook
jupyter notebook Ex1.ipynb
```

### What Each Notebook Contains

- 📥 **Data Loading** - Import and prepare datasets
- 🔧 **Preprocessing** - Clean and transform data
- 🏗️ **Model Architecture** - Define network structure
- 🎯 **Training Loop** - Train the model
- 📊 **Evaluation** - Test and validate performance
- 📈 **Visualization** - Plot results and metrics

---

## 🛠️ Technologies Used

<div align="center">

| Category | Technologies |
|----------|--------------|
| **Frameworks** | ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) |
| **Libraries** | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=python&logoColor=white) |
| **Tools** | ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) |

</div>

### 🧩 Architectures Implemented

- **CNNs** - Convolutional Neural Networks
- **ResNet50** - Residual Networks
- **U-Net** - Semantic Segmentation
- **Faster R-CNN** - Object Detection
- **Autoencoders** - Compression & Reconstruction
- **VAE** - Variational Autoencoders
- **GAN** - Generative Adversarial Networks

---

## 📈 Results

Each experiment produces comprehensive outputs including:

<table>
<tr>
<td width="50%">

### 📊 Metrics & Visualizations
- ✅ Accuracy/Loss curves
- ✅ Confusion matrices
- ✅ ROC curves
- ✅ Precision-Recall curves

</td>
<td width="50%">

### 🖼️ Visual Outputs
- ✅ Feature maps & activations
- ✅ Segmentation masks
- ✅ Reconstructed images
- ✅ Generated samples

</td>
</tr>
</table>

> 💡 **Tip:** Check individual experiment folders for detailed visualizations and results

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🔃 Open a Pull Request

Please open an issue first to discuss major changes.

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Your Name**

- 🌐 GitHub: [@yourusername](https://github.com/yourusername)
- 📧 Email: your.email@example.com
- 💼 LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)

---

## 📝 Important Notes

> ⚠️ **GPU Memory:** Experiments 10-14 require substantial GPU memory (8GB+ recommended)

> 📥 **Datasets:** Download all datasets before running notebooks

> ⏱️ **Training Time:** Some models may take several hours to train

> 🔄 **Updates:** Repository is actively maintained and updated

---

## 🌟 Star History

If you find this repository helpful, please consider giving it a ⭐!

---

<div align="center">

### 📅 Last Updated: November 2025

### ✅ Status: All Experiments Completed

**Made with ❤️ by Harsh Chaudhary**

</div>