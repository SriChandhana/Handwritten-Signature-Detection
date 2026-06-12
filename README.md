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

⚙️ Methodology
1. Data Preprocessing
Grayscale conversion
Image resizing
Normalization
Noise removal
Data augmentation
2. Feature Learning
Siamese CNN extracts signature embeddings
Shared-weight architecture ensures consistent learning
3. Similarity Computation
Computes distance between embeddings
Generates similarity score
4. Verification
Similarity score is evaluated
Signature classified as:
Genuine
Forged
📊 Results
Model	Accuracy
CNN	53.00%
Siamese CNN	87.31%
Key Outcomes
Achieved 87.31% verification accuracy using Siamese CNN.
Significantly outperformed standard CNN architecture.
Successfully differentiated genuine and forged signatures.
Demonstrated effectiveness for authentication systems.
🛠️ Tech Stack
Machine Learning
Python
TensorFlow
Keras
Computer Vision
OpenCV
NumPy
Data Analysis
Pandas
Visualization
Matplotlib
Seaborn
Backend
Flask
Frontend
HTML
CSS
JavaScript
📚 Dataset
CEDAR Signature Dataset

The project uses the CEDAR Signature Dataset containing:

Genuine signatures
Skilled forgeries
Multiple users
Signature verification pairs

This dataset is widely used in offline signature verification research.

📸 Screenshots
1️⃣ Siamese CNN Architecture

Screenshot Source: Figure 2 from project report

Save as:

docs/siamese-cnn-architecture.png

Add:

### Siamese CNN Architecture

![Siamese CNN](docs/siamese-cnn-architecture.png)
2️⃣ Signature Verification Workflow

Screenshot Source: Figure 3 (Workflow Diagram)

Save as:

docs/workflow.png

Add:

### Signature Verification Workflow

![Workflow](docs/workflow.png)
3️⃣ Web Application Home Page

Screenshot Source: Figure 7 (User Interface)

Save as:

docs/home-page.png

Add:

### Web Application Interface

![Home Page](docs/home-page.png)
4️⃣ User Registration

Screenshot Source: Figure 8

Save as:

docs/user-registration.png

Add:

### User Registration

![Registration](docs/user-registration.png)
5️⃣ Genuine Signature Verification

Screenshot Source: Figure 10

Save as:

docs/genuine-signature.png

Add:

### Genuine Signature Detection

![Genuine Signature](docs/genuine-signature.png)
6️⃣ Forged Signature Detection

Screenshot Source: Figure 12

Save as:

docs/forged-signature.png

Add:

### Forged Signature Detection

![Forged Signature](docs/forged-signature.png)
📂 Project Structure
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
🔬 Research Foundation

The project is inspired by research in:

Siamese Neural Networks
Signature Verification
Metric Learning
Deep Learning-based Authentication

Key references include:

Bromley et al. (1993)
Hafemann et al. (2017)
SigNet (2017)
Koch et al. (2015)
🔮 Future Improvements
Vision Transformers (ViT)
Attention-based verification
Mobile deployment
Real-time authentication
Multi-factor verification systems
Large-scale user verification
👩‍💻 Author

Kandula Sri Chandhana
B.Tech CSE (Artificial Intelligence & Machine Learning)
VNR VJIET
