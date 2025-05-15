# Arabic Handwritten Character Recognition 📝🇸🇦
This project focuses on building a deep learning model to recognize handwritten Arabic characters using the [Arabic Handwritten Characters Dataset (AHCD)](https://www.kaggle.com/datasets/mloey1/ahcd1). The notebook walks through data preprocessing, model training, evaluation, and prediction steps using TensorFlow and Keras.

## 📁 Project Structure
📦arabic_character_recognition

┣ 📜arabic_character_recognition.ipynb

┗ 📜README.md

🧾 Requirements

Python 3.7+

TensorFlow

NumPy

Pandas

Matplotlib

scikit-learn

seaborn

## 🚀 Features
- Preprocessing and visualization of Arabic handwritten characters
- 
- CNN architecture using TensorFlow/Keras
- 
- Accuracy and loss plots for model evaluation
- 
- Confusion matrix for performance analysis
- 
- Prediction demonstration on sample images

## 🧠 Model Architecture
The model is a Convolutional Neural Network (CNN) with the following structure:

- Convolutional + MaxPooling layers
- 
- Dropout regularization
- 
- Fully connected (Dense) layers
- 
- Softmax activation for 28 Arabic characters
- 

## 📊 Dataset
- **Name**: AHCD (Arabic Handwritten Characters Dataset)
- **Classes**: 28 Arabic letters
- **Images**: Grayscale, 32x32 pixels
- **Format**: `.csv` (images flattened into rows)

You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/mloey1/ahcd1).
