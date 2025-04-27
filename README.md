# 🦟 Malaria Detection using Deep Learning 🧠

## 🔬 Turning Pixels into Diagnoses

This project harnesses the power of Convolutional Neural Networks (CNNs) to automatically detect malaria parasites in microscopic blood smear images, potentially saving lives through faster and more accurate diagnoses.

## 📊 Dataset Breakdown
| Set | Images | Format |
|-----|--------|--------|
| Training | 13,152 | 224x224 JPEG |
| Validation | 626 | 224x224 JPEG |
| Test | 1,253 | 224x224 JPEG |

## 🏗️ Model Architecture
- 🧱 3 Conv2D layers for feature extraction
- 🏊‍♂️ MaxPooling layers to reduce dimensionality
- 💧 Dropout layers to prevent overfitting
- 🔌 Fully connected Dense layers for classification
- 🎯 **93.45%** accuracy achieved on test set

## 🛠️ Tech Stack
- TensorFlow & Keras for deep learning
- Matplotlib & Seaborn for visualization
- Python 3.x as the foundation

## 🚀 Quick Start Guide
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Load the dataset
4. Train the model: `python train.py`
5. Evaluate results: `python evaluate.py`

## 📈 Results Preview
Our model demonstrates robust performance in distinguishing between infected and uninfected cells, with potential applications in resource-limited healthcare settings.

## 👨‍💻 Author
Developed by **Randell Mwania**

---
*Fighting malaria one pixel at a time* 💪