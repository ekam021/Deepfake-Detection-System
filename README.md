# DeepGuard - AI-Powered Deepfake Detection System

## OVERVIEW

DeepGuard is a deep learning-based deepfake detection system designed to identify whether a facial image is authentic or AI-generated. The system combines state-of-the-art computer vision techniques, transfer learning, and explainable AI to provide accurate and interpretable deepfake detection.

Built on the EfficientNetB3 architecture and powered by GradCAM explainability, DeepGuard not only classifies images as Real or Fake but also visualizes the facial regions that influenced the model's decision.

---

## PROBLEM STATEMENT

With the rapid advancement of Generative AI, creating highly realistic fake images and videos has become easier than ever. Deepfakes pose serious threats to personal privacy, digital trust, media authenticity, and cybersecurity.

Identifying manipulated content manually is increasingly difficult as modern deepfake generation techniques produce visually convincing results that can deceive both humans and traditional detection methods.

DeepGuard addresses this challenge by allowing users to upload facial images and instantly determine whether they are authentic or AI-generated.

The system can answer questions such as:

* Is this image real or AI-generated?
* How confident is the prediction?
* Which facial regions influenced the model's decision?
* What visual artifacts indicate possible manipulation?

Using deep learning, transfer learning, and explainable AI, DeepGuard provides accurate predictions along with visual evidence to support every classification.

---

## KEY FEATURES

* Deepfake Detection using EfficientNetB3
* Face Extraction using MTCNN
* Two-Phase Transfer Learning Strategy
* GradCAM Explainability
* Real-Time Prediction Interface
* Confidence Score Visualization
* Class Imbalance Handling with Class Weights
* Data Augmentation and Regularization
* Interactive Gradio Web Application
* Explainable AI (XAI) for Prediction Transparency

---

## TECHNOLOGY STACK

### Programming Language

* Python

### Deep Learning

* TensorFlow
* Keras
* EfficientNetB3
* Transfer Learning

### Computer Vision

* OpenCV
* MTCNN
* Image Processing

### Explainable AI

* GradCAM
* TensorFlow GradientTape

### Data Science

* NumPy
* Pandas
* Scikit-Learn

### Deployment & Interface

* Gradio
* Kaggle GPU Environment

---

## SYSTEM ARCHITECTURE

1. Image Upload
2. Face Detection using MTCNN
3. Face Cropping & Preprocessing
4. EfficientNetB3 Feature Extraction
5. Deepfake Classification
6. Confidence Score Generation
7. GradCAM Heatmap Creation
8. Prediction Visualization
9. Result Delivery

---

## MODEL TRAINING STRATEGY

### Phase 1 - Feature Learning

* EfficientNetB3 backbone frozen
* Only classification head trained
* Learning Rate: 1e-3
* 15 Training Epochs

### Phase 2 - Fine Tuning

* Last 50 backbone layers unfrozen
* Fine-tuned using low learning rate
* Learning Rate: 1e-5
* Up to 25 Training Epochs

This two-phase training strategy improves domain adaptation while preserving pretrained ImageNet knowledge.

---

## PROJECT HIGHLIGHTS

* Built an end-to-end Deepfake Detection Pipeline
* Implemented MTCNN-based facial extraction
* Developed an Explainable AI framework using GradCAM
* Achieved approximately 90% Validation Accuracy
* Achieved approximately 0.90 F1-Score
* Achieved approximately 0.95 AUC Score
* Deployed through an interactive Gradio web interface
* Integrated real-time prediction and visualization capabilities

---

## TECHNICAL CHALLENGES SOLVED

* Accurate face extraction from raw images
* Detection of high-quality AI-generated faces
* Handling dataset imbalance during training
* Preventing model overfitting
* Building interpretable deep learning predictions
* Creating user-friendly deployment interfaces
* Improving classification performance through transfer learning

---
<img width="1366" height="1229" alt="FireShot Capture 013 - DeepGuard · Deepfake Detector -  d2d43d00e55efdf2bb gradio live" src="https://github.com/user-attachments/assets/e4048a2e-cb75-4a0a-a2aa-c33dcc6e3e7c" />

<img width="1039" height="554" alt="Screenshot 2026-05-10 231848" src="https://github.com/user-attachments/assets/53e1209a-d5e0-414a-a8dd-601cdfd2c172" />


<img width="1058" height="601" alt="Screenshot 2026-05-10 232014" src="https://github.com/user-attachments/assets/e28a5fac-f528-4e33-96ce-9a51cdd8bf1f" />


<img width="1079" height="595" alt="Screenshot 2026-05-10 232216" src="https://github.com/user-attachments/assets/4b161d92-1fc5-4d31-b8bc-7e591e8833b8" />
