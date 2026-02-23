# 🩺 Pneumonia Detection Using Deep Learning  

This work explores pneumonia detection using the PneumoniaMNIST dataset by benchmarking a baseline CNN against deeper architectures such as DenseNet121. The first experimental setting restricts training to a minimal, class-balanced subset of samples per class, excluding the use of pretrained models or auxiliary datasets. Within this constrained framework, fiine tune CNN model consistently outperforms the baseline CNN, underscoring the advantage of residual learning in low-data scenarios. Subsequently, the study extends to a transfer learning paradigm, where DenseNet121 pretrained on ImageNet is employed. The integration of pretrained knowledge leads to marked improvements in classification accuracy and generalization, emphasizing the importance of deep feature reuse and external representation learning in medical imaging applications.

## 📌 Overview
This project implements a transfer learning-based deep learning model for automatic pneumonia detection from chest X-ray images.

## 🔧 Tech Stack
- Python
- PyTorch
- DenseNet121
- MedMNIST
- Finetuned CNN

## 📊 Results
- Accuracy: 94%
- Presicion: 0.98

## 🚀 How to Run
```bash
pip install -q medmnist torch torchvision scikit-learn matplotlib seaborn faiss-cpu transformers accelerate pil
pip install -r requirements.txt


