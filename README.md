# 🩺Pnemonia Detection Challenge: AI Medical Imaging System

This repository contains a complete end-to-end AI system developed as part of the Challenge on AI Medical Imaging, Visual Language Models, and Semantic Retrieval.

The system integrates three interconnected tasks using the PneumoniaMNIST (MedMNIST v2) dataset:

1.CNN-based pneumonia classification
2.Medical report generation using a visual language model (VLM)
3.Semantic image retrieval using medical image embeddings and a vector database


This work presents a comprehensive end-to-end AI framework for pneumonia analysis using the PneumoniaMNIST dataset, integrating image classification, medical report generation, and semantic image retrieval. In the first stage, a convolutional neural network–based classifier is developed to distinguish between normal and pneumonia chest X-ray images using a rigorously designed training, validation, and testing pipeline. Medical-image–specific preprocessing, data augmentation, and systematic evaluation using accuracy, precision, recall, F1-score, and ROC-AUC demonstrate the robustness of the classification model, while confusion matrix analysis and failure case visualization provide insights into model limitations. 

Building upon the classification results, the second stage incorporates a medical visual language model to generate clinically meaningful radiology-style reports directly from chest X-ray images. Prompt-engineered report generation enables qualitative comparison between model predictions, ground-truth labels, and linguistic descriptions, highlighting the interpretability and complementary role of multimodal models in clinical decision support. Finally, the framework is extended to a semantic image retrieval system, where learned image embeddings and a FAISS-based vector index enable both image-to-image and text-to-image retrieval. 

Retrieval performance is quantitatively assessed using Precision@k and qualitatively analyzed through visual inspection of retrieved cases. Together, these components demonstrate a unified, reproducible pipeline that combines diagnosis, explanation, and case-based reasoning, illustrating the potential of integrated multimodal AI systems for medical imaging applications.

## 📌 Overview
This project implements a transfer learning-based deep learning model for automatic pneumonia detection from chest X-ray images.

## 🔧 Tech Stack
- Python
- PyTorch
- DenseNet121
- Resnet50
- MedMNIST
- CNN

## 📊 Results
- Accuracy: 94%
- Presicion: 0.98

## 🚀 How to Run
```bash
pip install -q medmnist torch torchvision scikit-learn matplotlib seaborn faiss-cpu transformers accelerate pil
pip install -r requirements.txt


