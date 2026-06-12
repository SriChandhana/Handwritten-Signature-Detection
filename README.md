# ✍️ Fake Handwritten Signature Detection using Siamese CNN

A deep learning-based signature verification system designed to distinguish genuine signatures from forged signatures using a Siamese Convolutional Neural Network (Siamese CNN). The system learns similarity patterns between pairs of signatures and provides an automated solution for fraud detection, identity verification, and document authentication.

---

## 📖 Overview

Handwritten signatures remain one of the most widely used methods for authentication in banking, legal documentation, and digital identity verification. Manual verification is time-consuming and prone to human error.

This project automates signature verification using deep learning and image processing techniques. By leveraging a Siamese CNN architecture, the system compares pairs of signatures and determines whether they belong to the same individual based on learned feature embeddings and similarity scores.

---

## 🚀 Features

### 🔍 Signature Verification
- Genuine vs forged signature detection
- Pairwise signature comparison
- Similarity-based authentication
- Writer-independent verification

### 🧠 Deep Learning
- Siamese CNN architecture with shared weights
- Feature embedding generation
- Distance-based similarity learning
- Binary similarity prediction

### 🖼️ Image Processing
- Grayscale conversion
- Image resizing
- Image normalization
- Noise reduction
- Data augmentation

### 🌐 Web Application
- Flask-based interface
- User registration
- Genuine signature upload
- Signature verification portal
- Real-time prediction results

### 🛡️ Security Applications
- Fraud detection
- Banking authentication
- Legal document verification
- Digital identity verification

---

## 🏗️ System Architecture

```text
Signature A               Signature B
     │                         │
     ▼                         ▼
 Shared CNN Network     Shared CNN Network
     │                         │
     ▼                         ▼
 Feature Embedding      Feature Embedding
            │
            ▼
     Distance Function
            │
            ▼
      Similarity Score
            │
            ▼
     Genuine / Forged
