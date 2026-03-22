# Deep Learning-Based Image Classification for Urban vs Natural Scene Detection (CNN & ResNet50)

## Description
This project focuses on building a deep learning model to classify images as **buildings or forests** using a dataset of approximately **5,000 images**. The goal is to develop and optimize image classification models using both custom CNN architecture and transfer learning techniques.

---

## Dataset
- **Total Images:** ~5,000  
- **Training Set:** ~4,000 images  
- **Test Set:** ~1,000 images  
- **Classes:** Building, Forest  

Dataset Source: https://www.kaggle.com/datasets/mhmmadalewi/buildings-vs-forests  

---

## Approach

### 1. Data Preprocessing
- Rescaled pixel values (0–1 normalization)  
- Image resizing to 256x256  
- Train-validation split (80/20)  

---

### 2. CNN Model (From Scratch)
- Conv2D + MaxPooling layers for feature extraction  
- Dense layers for classification  
- Binary crossentropy loss with Adam optimizer  

---

### 3. Model Improvement
- Applied **Batch Normalization** to stabilize training  
- Added **Dropout layers** to reduce overfitting  
- Tuned learning rate for better convergence  

---

### 4. Transfer Learning (ResNet50)
- Used pre-trained **ResNet50 (ImageNet weights)**  
- Frozen base layers to retain learned features  
- Added custom classification layers  

---

### 5. Evaluation
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-score)  

---

## Key Highlights
- Built and compared **multiple deep learning models**  
- Applied **regularization techniques** to improve performance  
- Leveraged **transfer learning for better accuracy**  
- Demonstrated end-to-end image classification pipeline  



## Tools & Technologies
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## Outcome
Successfully developed and optimized image classification models, demonstrating strong capability in **deep learning, model tuning, and evaluation for computer vision tasks**.

---
