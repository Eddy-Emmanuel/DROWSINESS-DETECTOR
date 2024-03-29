# YAWN-EYE-DETECTOR

## Overview
YAWN-EYE-DETECTOR is a deep learning project focused on detecting yawning and eye closure in images. It employs transfer learning with MobileNet as the base model for feature extraction and a custom classifier for prediction. This project can be utilized in various applications such as drowsiness detection systems for drivers or monitoring fatigue levels in individuals.

## Motivation
Drowsy driving is a significant cause of road accidents worldwide. Identifying signs of drowsiness, such as yawning and eye closure, can play a crucial role in preventing accidents and saving lives. YAWN-EYE-DETECTOR aims to contribute to this effort by providing an efficient and accurate solution for detecting these signs in real-time through image analysis.

## Dataset
The dataset used for training and testing the model is available [here](/kaggle/input/yawn-eye-dataset-new/dataset_new). It comprises images categorized into yawning and non-yawning instances, as well as open and closed eyes. The dataset is essential for training a robust model capable of generalizing well to real-world scenarios.

## Requirements
- Python 3.x
- TensorFlow
- NumPy
- Keras
- OpenCV (optional, for image processing)
- Jupyter Notebook (optional, for experimenting)

