# American Sign Language Recognition

A deep learning-based **Sign Language Recognition** system designed to facilitate communication between **signers** and **non-signers**. The project focuses on recognizing hand gestures from camera input and translating them into meaningful characters, numbers, words, and phrases.

> 📄 **Research Paper:** [IEEE Xplore](https://ieeexplore.ieee.org/document/10307541)

---

## 📌 Overview

Communication between the deaf and hard-of-hearing community and people unfamiliar with sign language can be challenging due to the communication gap between signers and non-signers.

This project develops a computer vision-based system that recognizes sign language gestures captured through a camera and converts them into textual representations.

**Camera Input → Image Preprocessing → CNN → Sign Prediction → Text**

---

## ✨ Key Contributions

* **Custom Dataset:** Created a dedicated dataset of sign language gestures, including alphabets, numbers, and selected words and phrases.
* **Novel Preprocessing:** Developed a specialized image preprocessing approach to improve the representation of hand gestures for recognition.
* **CNN-Based Recognition:** Designed and trained a Convolutional Neural Network for sign classification.
* **Communication-Oriented Design:** Extended recognition beyond individual signs to include selected words and phrases, with the goal of enabling more practical end-to-end communication.

---

## 🧠 Model

The system uses a **Convolutional Neural Network (CNN)** trained on the custom-collected dataset.

The model operates on preprocessed grayscale hand-gesture images and performs multi-class classification across **53 sign categories**.

Training incorporates image augmentation to improve model robustness and generalization.

---

## 🏗️ System Pipeline

```text
Webcam Input
     ↓
Hand Gesture Preprocessing
     ↓
CNN-Based Recognition
     ↓
Predicted Sign
     ↓
Textual Output
```

---

## 📂 Repository

```text
.
├── ASL_LNET_1400_mixedfinal.ipynb   # Model training
├── datacollectionfinal.ipynb        # Dataset collection
├── MODEL_WF-mixed_V4.json           # Model architecture
├── MODEL_WF-mixed_V4.h5             # Trained model
└── README.md
```

---

## 🛠️ Technologies

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Convolutional Neural Networks
* Computer Vision
* Deep Learning

---

## 📄 Publication

This work was published through **IEEE**.

**Paper:** [Sign Language Recognition — IEEE Xplore](https://ieeexplore.ieee.org/document/10307541)

The paper presents the proposed recognition system, custom dataset, preprocessing methodology, and the extension toward recognizing words and phrases.

---
