# 🩺 Laparoscopic Organs Detection

## 📌 Overview
This project focuses on **organ detection and classification** from laparoscopic surgical images using deep learning techniques. The goal is to assist surgeons during minimally invasive surgeries by automatically identifying organs, improving navigation, reducing operation time, and minimizing risks.

This work is part of our **final year B.Tech project**.

---

## 🎯 Objectives
- Build an AI-powered system to classify organs in laparoscopic surgery images.
- Leverage deep learning models to achieve high accuracy in real-world scenarios.
- Lay the groundwork for integration into real-time surgical assistance tools.

---

## 📂 Repository Structure
├── dataset.ipynb # Dataset preprocessing and preparation
├── yash.ipynb # Model training and evaluation
├── README.md # Project documentation
└── requirements.txt # Python dependencies

yaml
Copy
Edit

---

## 🛠️ Methodology
1. **Dataset Preparation**
   - Collected laparoscopic images from publicly available datasets.
   - Preprocessed data (resizing, normalization, augmentation).
   - Created labeled datasets for training.

2. **Model Development**
   - Implemented deep learning architectures for classification.
   - Used convolutional neural networks (CNNs) for feature extraction.

3. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score.
   - Cross-validation for robust results.

---

## 📊 Results
- Achieved strong classification performance on multiple organs.
- Demonstrated the feasibility of real-time organ recognition.
- Potential for integration with surgical navigation systems.

---

## 📦 Installation & Usage
### Prerequisites
- Python 3.8+
- Jupyter Notebook
- TensorFlow or PyTorch
- OpenCV, NumPy, Pandas, Matplotlib

### Setup
`
git clone https://github.com/shxrky17/Lapascopic-Organs-Detection.git
cd Lapascopic-Organs-Detection
pip install -r requirements.txt
`
Running
Open dataset.ipynb to preprocess the dataset.

Open yash.ipynb to train and test the model.

## 📁 Dataset
Dataset: Laparoscopic surgery images with organ annotations.

Due to data privacy, the dataset is not included in this repository. Contact the authors for access.

## 📚 Literature Survey
Many laparoscopic image analysis methods depend on manual annotation or basic image processing. Our approach automates the classification process using deep learning, increasing accuracy and reducing dependency on human input.

## 🚀 Future Enhancements
Improve model accuracy with larger and more diverse datasets.

Real-time processing from live surgical feeds.

Integrate with augmented reality surgical guidance systems.

## 👥 Team Members
Ayush Aote
Yash Chafle
Atharva Joshi
Swagat Koreti
Prathamesh Patil
Vedant Itankar

Mentor: Prof. Ganesh Yenurkar

Yash Chafle

Mentor: [Mentor’s Name]
