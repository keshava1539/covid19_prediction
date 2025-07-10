COVID-19/Pneumonia X-ray Image Classification
This repository contains a deep learning project aimed at classifying Chest X-ray images to detect whether a patient has Normal lungs or Pneumonia. This can be a valuable tool for assisting in the rapid screening or preliminary diagnosis of respiratory conditions, including those potentially associated with COVID-19.

Project Goal
The primary objective of this project is to build and train a Convolutional Neural Network (CNN) model capable of accurately distinguishing between normal and pneumonia-affected lung X-rays.

Dataset
The model is designed to work with a dataset structured in directories, typically organized as:

xray_dataset_covid19/
├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
└── test/
   ├── NORMAL/
   └── PNEUMONIA/

The notebook specifically loads data from xray_dataset_covid19/train. The two classes identified are NORMAL and PNEUMONIA.

Methodology
The project utilizes a CNN architecture for image classification, implemented using TensorFlow and Keras. Key preprocessing steps and configurations include:

Image Resizing: All input images are resized to a uniform dimension of 256x256 pixels.

Color Channels: Images are processed with 3 color channels (RGB).

Batch Processing: Data is loaded in batches of 32 for efficient training.

Data Loading: tf.keras.preprocessing.image_dataset_from_directory is used for efficient data loading directly from the directory structure, handling automatic labeling and initial resizing.

Technologies Used
Python

TensorFlow

Keras

Matplotlib (for visualization, likely during data exploration or model evaluation)

