# 😷 Face Mask Detection Using CNN

This project detects whether a person is wearing a face mask using deep learning with Convolutional Neural Networks (CNN). It classifies images into two categories: **With Mask** and **Without Mask**.

---

## 🧠 Model Architecture

- Input: Resized face image (e.g., 100x100 or 224x224)
- CNN layers with ReLU activations
- MaxPooling layers to reduce spatial dimensions
- Fully connected dense layers
- Output: Binary classification (0 = No Mask, 1 = Mask)

---

## 🗃️ Dataset

- **Classes**: With Mask, Without Mask  
- **Source**: Public face mask datasets (e.g., Kaggle or GitHub)
- Images are preprocessed (resized, normalized) before training

---

## 🧪 Model Training

- Framework: TensorFlow/Keras
- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Accuracy: Achieved ~95% validation accuracy

---

## 📂 Project Structure

├── face_mask_model.h5 # Trained Keras model
├── face_mask_detector.py # Code for training and prediction
├── dataset/ # Folder containing mask/no-mask images
├── detect_live.py # Real-time detection via webcam
├── README.md # This file

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/face-mask-detector
   cd face-mask-detector

pip install tensorflow opencv-python numpy
python detect_live.py

