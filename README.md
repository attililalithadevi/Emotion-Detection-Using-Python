# Emotion-Detection-Using-Python
Developed a machine learning model on Google Colab to detect human emotions.

Introduction:

This project aims to classify the emotion on a person's face into one of seven categories, using deep convolutional neural networks. The model is trained on the FER-2013 dataset which was published on International Conference on Machine Learning (ICML). This dataset consists of 35887 grayscale, 48x48 sized face images with seven emotions - angry, disgusted, fearful, happy, neutral, sad and surprised.

Dependencies:

Python 3, OpenCV, Tensorflow
To install the required packages, run pip install -r requirements.txt.
Basic Usage
The repository is currently compatible with tensorflow-2.0 and makes use of the Keras API using the tensorflow.keras library.

src:

data (folder)
emotions.py (file)
haarcascade_frontalface_default.xml (file)
model.h5 (file)
This implementation by default detects emotions on all faces in the webcam feed. With a simple 4-layer CNN, the test accuracy reached 63.2% in 50 epochs.

Accuracy plot

Data Preparation (optional)
The original FER2013 dataset in Kaggle is available as a single csv file. I had converted into a dataset of images in the PNG format for training/testing.

In case you are looking to experiment with new datasets, you may have to deal with data in the csv format. I have provided the code I wrote for data preprocessing in the dataset_prepare.py file which can be used for reference.
