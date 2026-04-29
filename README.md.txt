# Computer Vision Assignment 3
## PCB Defect Detection / Pneumonia Diagnosis

---

## Student Information
- Name: Ali Hussain 
- Roll Number: 22F-3794
- Section: BS(EE)-8A
- Course: CS4059 - Fundamentals of Computer Vision

---

## Project Overview
This project focuses on two important computer vision applications:

### 1. PCB Defect Detection
This task involves automatic detection of defects in Printed Circuit Boards (PCBs) using deep learning techniques. The following models were implemented:
- A custom Convolutional Neural Network (CNN)
- A pretrained ResNet model using transfer learning  

The goal is to classify different types of PCB defects such as missing holes, open circuits, mouse bites, and short circuits.

### 2. Pneumonia Detection
This task involves detecting pneumonia from chest X-ray images. Two approaches were used:
- Fully Convolutional Network (FCN)
- Autoencoder for anomaly detection  

The objective is to assist in medical diagnosis using deep learning models.

---

## Repository Structure
├── Q1_PCB_Defect_Detection/
│ ├── data/
│ ├── pcb_cnn.ipynb
│ ├── pcb_resnet.ipynb
│
├── Q2_Pneumonia_Detection/
│ ├── data/
│ ├── pneumonia_fcn.ipynb
│ ├── pneumonia_autoencoder.ipynb
│
├── requirements.txt
└── README.md

---

## Environment Setup

### Requirements
- Python 3.8 or higher
- CUDA-capable GPU (recommended: Google Colab)

### Installation
Install all dependencies using:
```bash
pip install -r requirements.txt
Running the Code
(For Question 1)
# Open notebooks in Google Colab

# Run basic CNN model
pcb_cnn.ipynb

# Run ResNet model
pcb_resnet.ipynb
(For Question 2)
# Open notebooks in Google Colab

# Run FCN model
pneumonia_fcn.ipynb

# Run Autoencoder model
pneumonia_autoencoder.ipynb
Results Summary
PCB Defect Detection
CNN Accuracy: ~85%
ResNet Accuracy: ~92%
Best Model: ResNet (Transfer Learning)
Pneumonia Detection
FCN Sensitivity: ~88%
Autoencoder AUC: ~90%
Recommended Approach: FCN for classification and Autoencoder for anomaly detection