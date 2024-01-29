# Handwritten-Digits-Recognition-in-Both-Arabic-and-English
This cutting-edge project maximizes digit recognition! Employing Neural Networks, SVM, and Random Forest, it achieves top-tier accuracy, precision, recall, and F1 scores. Hyperparameter tuning, pre-processing, and insightful comparative analysis propel these models to new heights! 🚀

This project focuses on the intricate task of recognizing handwritten digits, employing two distinct datasets—one in Arabic and another in English. Three models, each tailored to the characteristics of the respective languages, constitute the core of the approach.

The Neural Network, structured sequentially, adapts its hidden layers and neurons dynamically, utilizing activation functions like ReLU, Tanh, and Sigmoid. Training involves reshaping image pixels and dataset split, while Keras Tuner's Hyperband optimizes hyperparameters such as activation, layers, neurons, learning rate, batch size, and epochs. Evaluation is grounded in accuracy.

The SVM model, employing an RBF kernel and PCA for feature extraction, engages in reshaping, dataset split, and grid search for gamma and regularization during training.

Random Forest, an ensemble of decision trees, utilizes bootstrap aggregating. Training involves dataset split and grid search for n_estimators and max_depth.

A common preprocessing framework unifies image pixel normalization, while model-specific steps are implemented for optimal performance.

Evaluation metrics encompass accuracy, recall, F1 score, and precision, visualized through confusion matrices. Results showcase high accuracy for both datasets, effective learning, and identified challenges, including missing testing labels for the English data



Find the datasets on Kaggle by following the following links:

English: https://www.kaggle.com/competitions/digit-recognizer/data

Arabic: https://www.kaggle.com/datasets/mloey1/ahdd1
