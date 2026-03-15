# Handwritten Digit Classification using CNN

## Project Overview

This project focuses on building a **Handwritten Digit Recognition system** using **Deep Learning (Convolutional Neural Networks - CNN)**. The goal of this project is to classify handwritten digits from **0 to 9** using the **MNIST dataset**.

Handwritten digit recognition has many real-world applications such as:

- Bank cheque processing  
- Postal code recognition  
- Automated form processing  
- Digitization of handwritten documents  

---

## Dataset

This project uses the **MNIST dataset**, which is a popular dataset in machine learning and deep learning.

Dataset details:

- Total Images: **70,000**
- Training Images: **60,000**
- Testing Images: **10,000**
- Image Size: **28 × 28 pixels**
- Image Type: **Grayscale**
- Number of Classes: **10 (digits 0–9)**

---

## Technologies Used

The following technologies and libraries are used in this project:

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- TensorFlow  
- Keras  
- Scikit-learn  

---

## Project Workflow

### 1. Data Loading
Loading the MNIST dataset using TensorFlow/Keras.

### 2. Data Preprocessing
- Image normalization
- Reshaping the data
- Label encoding

### 3. Exploratory Data Analysis
- Digit visualization
- PCA visualization
- UMAP visualization

### 4. Model Building
A **Convolutional Neural Network (CNN)** model is used to identify patterns in handwritten digits.

### 5. Model Training
The CNN model is trained on the training dataset.

### 6. Model Evaluation
The trained model is evaluated on the test dataset to measure accuracy.

---

## Model Architecture

The CNN model consists of:

- Convolution Layers  
- MaxPooling Layers  
- Dense Layers  
- Softmax Output Layer  

---

## Results

The trained model successfully classifies handwritten digits with **high accuracy on the MNIST test dataset**.

---

## Project Structure

```
Handwritten-Digit-Classification
│
├── Handwritten_Digit_Classification.ipynb
├── README.md
└── requirements.txt
```

---

## Applications

- Optical Character Recognition (OCR)
- Bank cheque processing
- Postal mail sorting
- Digit recognition systems

---

## Future Improvements

- Improve model accuracy using advanced CNN architectures  
- Apply data augmentation techniques  
- Deploy the model as a web application  
- Real-time digit recognition system  

---

## Author

**Diya Panwar**  
Data Scientist
