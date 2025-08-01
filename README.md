# breast-cancer-2
Breast Cancer Prediction using Machine Learning and Deep Learning
This project demonstrates a comprehensive approach to breast cancer diagnosis prediction using a dataset containing various features extracted from digitized images of fine needle aspirates (FNA) of breast masses. The project implements both a traditional Machine Learning model (Random Forest) and a Deep Learning model to classify tumors as either Malignant (M) or Benign (B).

The code includes robust data preprocessing steps, hyperparameter tuning with GridSearchCV, and advanced techniques to prevent common deep learning challenges like overfitting and vanishing gradients.

Features
Data Preprocessing: Handles data loading, feature-target separation, label encoding for the target variable, and feature scaling using StandardScaler.

Machine Learning Model: Utilizes a RandomForestClassifier with hyperparameter tuning via GridSearchCV to find the optimal model configuration.

Deep Learning Model: A multi-layer perceptron (MLP) built with TensorFlow/Keras, incorporating best practices for deep learning model design.

Overfitting Prevention: Implements L1 and L2 regularization, Max-norm regularization, and Dropout layers.

Vanishing Gradient Prevention: Uses He-uniform weight initialization, relu activation functions, and BatchNormalization.

Callbacks: Uses EarlyStopping to prevent overfitting during training and TensorBoard for model visualization and monitoring.
