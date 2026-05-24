

## Project Title
**Deep Learning**

---

## Author(s)
**Suhani Bode**

---

## Affiliation
**B.Tech Computer Science & Engineering (Data Science)**  
**Rashtrasant Tukadoji Maharaj Nagpur University**

---

## Date
**May 2026**

---

# Abstract

This project implements an image classification model using PyTorch and Transfer Learning. The CIFAR-10 dataset is used to classify images into 10 categories. A pretrained ResNet18 model is applied for faster and more accurate training. Data augmentation techniques improve model performance and reduce overfitting. The model is trained and evaluated in Google Colab using GPU support. Performance is analyzed using accuracy, loss graphs, confusion matrix, and classification report. The trained model can also predict custom images.

---

# Introduction

Image classification is a major application of Deep Learning and Computer Vision. This project aims to build an efficient image classifier using the CIFAR-10 dataset and a pretrained ResNet18 model. Transfer learning is used to reduce training time and improve accuracy.

---

# Literature Review

Traditional image classification methods used manual feature extraction techniques. Modern deep learning models like CNNs automatically learn image features and provide better performance. ResNet is a popular CNN architecture that improves training efficiency using residual connections. Transfer learning helps reuse pretrained models for new tasks.

---

# Methodology

The CIFAR-10 dataset is preprocessed using normalization and data augmentation techniques. A pretrained ResNet18 model is loaded and modified for 10-class classification. The model is trained using CrossEntropyLoss and Adam optimizer. Accuracy and loss are monitored during training, and the final model is evaluated on test data.

---

# Implementation

## Programming Language
- Python

## Frameworks/Libraries
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn

## Tools Used
- Google Colab
- GitHub

## Model
- ResNet18 (Pretrained)

## Dataset
- CIFAR-10

---

# Results and Discussion

The model achieved good classification accuracy on the CIFAR-10 dataset.

## Outputs
- Accuracy Graph
- Loss Graph
- Confusion Matrix
- Classification Report

## Accuracy
- Approximate Accuracy: 80%

The model performed well for most classes with minor confusion between similar objects.

---

# Limitation

- Small image size reduces feature details.
- Limited epochs due to computational constraints.
- Some classes are visually similar.

---

# Future Scope

- Use advanced models like ResNet50 or EfficientNet.
- Increase epochs for better accuracy.
- Deploy as a web application.
- Add real-time image prediction.

---

# Conclusion

This project successfully demonstrates image classification using PyTorch and transfer learning. The pretrained ResNet18 model provided good accuracy with reduced training time. The project helps understand deep learning, CNNs, and model evaluation techniques.
