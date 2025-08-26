# 🐶🐱 Cat vs Dog Classification Project

## Introduction
The objective of this project is to build a deep learning model that can classify images of cats and dogs.  
We use a **Convolutional Neural Network (CNN)** trained on the [Dogs vs Cats dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats) from Kaggle.  

The system preprocesses input images, trains a CNN model, and predicts whether a given image is a **cat 🐱** or a **dog 🐶**.  
This project also saves the trained model (`dog_cat_model.h5`) for future predictions without retraining.

---

## Modules Used

The following modules are used in this project:

- **TensorFlow / Keras**: Build and train the CNN model  
- **OpenCV**: Image preprocessing (resize, read, normalize)  
- **NumPy**: Numerical operations and array handling  
- **Matplotlib**: Visualize training history and predictions  
- **KaggleHub**: Download dataset directly from Kaggle  

---

## Trained Model

- [Saved Model (.h5)](dog_cat_model.h5)  

This file contains the trained CNN weights and can be reused for predictions.

---

## Dataset

- [Dogs vs Cats Dataset (Kaggle)](https://www.kaggle.com/datasets/salader/dogs-vs-cats)  

The dataset contains **25,000 images** of cats and dogs, split into training and testing sets.  

---

## Requirements

To run this project, you need the following dependencies installed:

- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- OpenCV  
- Matplotlib  
- KaggleHub  

Install them with:
```bash
pip install tensorflow opencv-python numpy matplotlib kagglehub
