# ✍️ Fake Handwritten Signature Detection using Siamese CNN

A deep learning-based signature verification system designed to distinguish genuine signatures from forged signatures using a Siamese Convolutional Neural Network (Siamese CNN). The system learns similarity patterns between pairs of signatures and provides an automated solution for fraud detection, identity verification, and document authentication.

---

## 📖 Overview

Handwritten signatures remain one of the most widely used methods for authentication in banking, legal documentation, and digital identity verification. Manual verification is time-consuming and prone to human error.

This project automates signature verification using deep learning and image processing techniques. By leveraging a Siamese CNN architecture, the system compares pairs of signatures and determines whether they belong to the same individual based on learned feature embeddings and similarity scores.

---

## 🚀 Features

### 🔍 Signature Verification

* Genuine vs forged signature detection
* Pairwise signature comparison
* Similarity-based authentication
* Writer-independent verification

### 🧠 Deep Learning

* Siamese CNN architecture with shared weights
* Feature embedding generation
* Distance-based similarity learning
* Binary similarity prediction

### 🖼️ Image Processing

* Grayscale conversion
* Image resizing
* Image normalization
* Noise reduction
* Data augmentation

### 🌐 Web Application

* Flask-based interface
* User registration
* Genuine signature upload
* Signature verification portal
* Real-time prediction results

### 🛡️ Security Applications

* Fraud detection
* Banking authentication
* Legal document verification
* Digital identity verification

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
```

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Grayscale conversion
* Image resizing
* Normalization
* Noise removal
* Data augmentation

### 2. Feature Learning

* Siamese CNN extracts signature embeddings
* Shared-weight architecture ensures consistent learning

### 3. Similarity Computation

* Computes distance between embeddings
* Generates similarity score

### 4. Verification

* Similarity score is evaluated
* Signature classified as:

  * Genuine
  * Forged

---

## 📊 Results

| Model       | Accuracy |
| ----------- | -------- |
| CNN         | 53.00%   |
| Siamese CNN | 87.31%   |

### Key Outcomes

* Achieved **87.31% verification accuracy** using Siamese CNN.
* Significantly outperformed standard CNN architecture.
* Successfully differentiated genuine and forged signatures.
* Demonstrated effectiveness for authentication systems.

---

## 🛠️ Tech Stack

### Machine Learning

* Python
* TensorFlow
* Keras

### Computer Vision

* OpenCV
* NumPy

### Data Analysis

* Pandas

### Visualization

* Matplotlib
* Seaborn

### Backend

* Flask

### Frontend

* HTML
* CSS
* JavaScript

---

## 📚 Dataset

### CEDAR Signature Dataset

The project uses the CEDAR Signature Dataset containing:

* Genuine signatures
* Skilled forgeries
* Multiple users
* Signature verification pairs

This dataset is widely used in offline signature verification research.

---

## 📸 Screenshots

### Siamese CNN Architecture

<img width="917" height="347" alt="image" src="https://github.com/user-attachments/assets/d17dea8a-6c6f-44eb-aa38-b1d646a3e6b2" />


### Signature Verification Workflow

<img width="891" height="427" alt="image" src="https://github.com/user-attachments/assets/ae3e42fb-aa5f-40db-902f-d9358f990bff" />


### Web Application Interface

<img width="740" height="488" alt="image" src="https://github.com/user-attachments/assets/e1de8447-3a16-4c3e-9e5b-3601cf5f027e" />


### User Registration

<img width="686" height="493" alt="image" src="https://github.com/user-attachments/assets/63224470-3265-4ea4-a4e3-8d2d1c26260b" />



### Genuine Signature Detection

<img width="538" height="506" alt="image" src="https://github.com/user-attachments/assets/29b42db3-1250-41cb-b4f3-62150cc4cc78" />


### Forged Signature Detection

<img width="503" height="476" alt="image" src="https://github.com/user-attachments/assets/02f60dfa-96b0-495d-8c7b-8bb884fe0e8b" />



## 📂 Project Structure

```text
project/
│
├── dataset/
├── preprocessing/
├── models/
├── training/
├── verification/
├── app/
├── docs/
│   ├── siamese-cnn-architecture.png
│   ├── workflow.png
│   ├── home-page.png
│   ├── user-registration.png
│   ├── genuine-signature.png
│   └── forged-signature.png
│
└── README.md
```

---

## 🔬 Research Foundation

The project is inspired by research in:

* Siamese Neural Networks
* Signature Verification
* Metric Learning
* Deep Learning-based Authentication

### Key References

* Bromley et al. (1993)
* Hafemann et al. (2017)
* SigNet (2017)
* Koch et al. (2015)

---

## 🔮 Future Improvements

* Vision Transformers (ViT)
* Attention-based verification
* Mobile deployment
* Real-time authentication
* Multi-factor verification systems
* Large-scale user verification

---

## ⭐ Applications

* Banking Authentication
* Fraud Detection
* Legal Document Verification
* Identity Verification
* Secure Access Systems

---

## 👩‍💻 Author

**Kandula Sri Chandhana**
B.Tech CSE (Artificial Intelligence & Machine Learning)
VNR VJIET
