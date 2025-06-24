# 🎯 Real-Time Digit Recognition Using CNN & OpenCV

This project is a beginner-friendly deep learning application that uses a Convolutional Neural Network (CNN) to recognize handwritten digits in real time using your webcam. The model is trained on the famous MNIST dataset and deployed using OpenCV for live predictions.

---

## 📌 Table of Contents

- [📚 About the Project](#-about-the-project)
- [🚀 Demo](#-demo)
- [🧠 Technologies Used](#-technologies-used)
- [🔧 Setup Instructions](#-setup-instructions)
- [📦 Installation](#-installation)
- [📊 Model Architecture](#-model-architecture)
- [📈 Training and Results](#-training-and-results)
- [📹 Real-Time Prediction](#-real-time-prediction)
- [📝 Future Improvements](#-future-improvements)
- [📄 License](#-license)

---

## 📚 About the Project

This project demonstrates a **digit classifier** trained on the MNIST dataset and integrated with your webcam to classify digits written in real time on a whiteboard or piece of paper.

**Goal:** Build a practical application that bridges the gap between deep learning models and real-time computer vision systems.

---

## 🚀 Demo

https://user-images.githubusercontent.com/demo.mp4 *(Replace this with a video link or gif if available)*

---

## 🧠 Technologies Used

- 🧮 TensorFlow / Keras
- 📊 MNIST Dataset
- 🎥 OpenCV for real-time video capture
- 🔢 NumPy, Matplotlib
- 🧪 Jupyter Notebook / Python 3

---

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/real-time-digit-recognition.git
   cd real-time-digit-recognition
(Optional but recommended) Create a virtual environment:

bash
Copy
Edit
conda create -n digit_recog python=3.9
conda activate digit_recog
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook
📦 Installation
List of key Python packages:

text
Copy
Edit
tensorflow
opencv-python
matplotlib
numpy
You can install them using:

bash
Copy
Edit
pip install tensorflow opencv-python matplotlib numpy
📊 Model Architecture
Input Layer: 28x28 grayscale images (1 channel)

Conv2D + MaxPooling2D (x2): Feature extraction

Flatten: Converts 2D to 1D

Dense (ReLU): Fully connected layer

Dense (Softmax): Output layer for 10 classes (0–9)

📈 Training and Results
Dataset: MNIST (60,000 training + 10,000 testing)

Accuracy Achieved: ~99% on test set

Epochs: 5

Loss Function: Sparse Categorical Crossentropy

Optimizer: Adam

📹 Real-Time Prediction
Once the model is trained:

Launch webcam using OpenCV.

Detect the ROI (region of interest) for the digit.

Preprocess (resize to 28x28, grayscale, invert color).

Predict using trained model.

Display prediction on live feed.

Run this script (example):

bash
Copy
Edit
python real_time_digit_recognition.py
Note: Make sure the lighting is good and write digits clearly for best results.

📝 Future Improvements
✍️ Add handwriting smoothing

🧼 Improve noise filtering using contour analysis

🌐 Deploy on web with Flask/Streamlit

📱 Android/iOS app using TensorFlow Lite

📄 License
This project is licensed under the MIT License.

🙌 Acknowledgements
MNIST Dataset

TensorFlow

OpenCV
