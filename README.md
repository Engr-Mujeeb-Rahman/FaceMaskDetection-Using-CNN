# Face Mask Detection using CNN

This project implements a **Face Mask Detection system** using a **Convolutional Neural Network (CNN)**.  
The model classifies images into two categories: **With Mask** and **Without Mask**.  
It is trained on an image dataset and deployed using **Streamlit** for image-based prediction.

The purpose of this project is to demonstrate the practical application of **Deep Learning and Computer Vision** using TensorFlow and Keras.

---

## Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Streamlit


---

## Model Architecture

The CNN architecture consists of:
- Three convolutional layers with **ReLU activation**
- Max pooling layers for spatial reduction
- Fully connected dense layers with **Dropout** to prevent overfitting
- A **sigmoid output layer** for binary classification

The model takes images resized to **128×128×3** as input.

---

## Dataset

The dataset contains two classes:
- **With Mask**
- **Without Mask**

Images are resized, normalized, and split into training and validation sets before training.

---

## How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/your-username/face-mask-detection-cnn.git
cd face-mask-detection-cnn
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the Streamlit app
```bash
streamlit run index.py
```
