COVID-19/Pneumonia X-ray Image Classification
📊 Overview
This project focuses on developing a deep learning model to classify Chest X-ray images. The goal is to accurately distinguish between Normal lung conditions and those indicative of Pneumonia. This can serve as a valuable tool for supporting the rapid screening and preliminary diagnosis of respiratory conditions.

👥 Contributor
Kallutla Veera Keshava Reddy

🧠 Project Highlights
Image-based Classification: Utilizes Convolutional Neural Networks (CNNs) for robust image analysis.

Disease Detection: Classifies X-ray images into 'NORMAL' and 'PNEUMONIA' categories.

Standardized Preprocessing: Implements image resizing to 256x256 pixels and uses 3 color channels (RGB) for consistent model input.

Efficient Data Loading: Leverages TensorFlow's image_dataset_from_directory for streamlined dataset management and batching.

🔍 Techniques Used
Python

TensorFlow

Keras (for building and training the neural network)

Matplotlib (for data visualization)

Deep Learning (CNNs)

Image Classification

📁 Files
model.ipynb: The main Jupyter Notebook containing the model definition, training, and evaluation code.

xray_dataset_covid19/: (Expected directory structure) The dataset should be organized into subdirectories for training, testing, and validation, with 'NORMAL' and 'PNEUMONIA' subfolders within each split.
