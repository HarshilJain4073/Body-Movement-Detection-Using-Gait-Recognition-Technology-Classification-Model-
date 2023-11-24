# Body-Movement-Detection-Using-Gait-Recognition-Technology-Classification-Model-
This repository contains code for a Body Movement Detection system using Gait Recognition Technology. The project utilizes machine learning techniques, specifically deep learning, to recognize different activities based on sensor data.

# Getting Started
Prerequisites
Python (3.6 or higher)
TensorFlow
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Install the required dependencies using:

pip install -r requirements.txt
# Code Overview
Data Loading and Preprocessing: The code reads sensor data from a CSV file, preprocesses it by scaling features, and encodes activity labels.

Model Building: A deep learning model is constructed using TensorFlow and Keras. It consists of input and output layers with intermediate dense layers.

Model Training: The model is trained using the training dataset with a validation split. Training loss and accuracy are monitored.

Evaluation: The trained model is evaluated on the test dataset, and metrics such as accuracy and confusion matrix are displayed.

Visualization: Loss, accuracy, and confusion matrix are visualized using Matplotlib and Seaborn.

# Results
The model achieves a test accuracy of 97%. Confusion matrix and other visualizations are available in the main folder(in the bottom).

# Future Work
Explore different architectures and hyperparameters for improved performance.
Investigate techniques for handling imbalanced datasets.
Extend the model to recognize new activities.
