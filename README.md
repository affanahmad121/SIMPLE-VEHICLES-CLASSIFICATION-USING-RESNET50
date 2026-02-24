# SIMPLE-VEHICLES-CLASSIFICATION-USING-RESNET50
This project implements a Vehicle Classification system using ResNet50 with transfer learning. The model is trained on labeled vehicle images and optimized using data augmentation and fine-tuning to improve accuracy.

#  Vehicle Classification using ResNet50

![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Keras](https://img.shields.io/badge/Keras-ResNet50-red)
![GPU](https://img.shields.io/badge/GPU-Tesla%20P100-green)
![Accuracy](https://img.shields.io/badge/Accuracy-94%25-brightgreen)

---

##  Project Overview

This project implements a **Multi-Class Vehicle Image Classification System** using **ResNet50 (Transfer Learning)**.  
The model is trained on a Kaggle vehicle dataset and achieves:

-  Training Accuracy: **94%**
-  Validation Accuracy: **91.2%**

The project demonstrates the effective use of **Transfer Learning, Data Augmentation, and Fine-Tuning** for high-performance image classification.

---

##  Model Architecture

We use:

-  Pretrained **ResNet50** (ImageNet weights)
-  Global Average Pooling
-  Fully Connected Dense Layers
-  Softmax Output Layer (Multi-class)

Transfer learning significantly reduces training time and improves performance.

---

##  Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Kaggle Notebook
- GPU: Tesla P100

---

##  Dataset

- Source: Kaggle
- Type: Multi-class vehicle image dataset
- Images resized to: 224x224
- Data preprocessing using `ImageDataGenerator`

---

##  Training Details

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Batch Size: 32
- GPU Used: Tesla P100
- Transfer Learning + Fine-Tuning

---

##  Results

| Metric | Value |
|--------|--------|
| Training Accuracy | 94% |
| Validation Accuracy | 91.2% |

The model generalizes well with minimal overfitting.

---

##  How to Run

```bash
git clone https://github.com/your-username/vehicle-classification-resnet50.git
cd vehicle-classification-resnet50
pip install -r requirements.txt

---
##AUTHOR-
- AFFAN AHMAD 
