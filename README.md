# iris-classification-ML-model
A Machine Learning-based web application built with Streamlit that predicts the species of iris flowers — Setosa, Versicolor, or Virginica — using their sepal and petal measurements.
This project demonstrates end-to-end ML workflow: from data preprocessing and model training to web deployment.

🚀 Overview
The Iris Classification App uses a trained ML model to classify iris flowers into one of three species based on input features:
Sepal Length
Sepal Width
Petal Length
Petal Width
Users can easily enter these values through an interactive web interface and get instant predictions.

🧠 Dataset
Dataset Name: Iris Dataset
Source: UCI Machine Learning Repository
Classes: Setosa, Versicolor, Virginica
Features: 4 numerical attributes (sepal length, sepal width, petal length, petal width)

⚙️ Model Training
The model was trained using Scikit-learn with the following steps:
1. Data preprocessing (cleaning and normalization)
2. Splitting dataset into training and testing sets
3. Training with a classification algorithm (e.g., Logistic Regression / SVM / RandomForest)
4. Evaluating model accuracy

💻 Tech Stack
Python
Streamlit – for web interface
Scikit-learn – for model building
Pandas, NumPy – for data handling
Matplotlib / Seaborn – for visualization

🌐 Deployment
The project is deployed using Streamlit Sharing / Streamlit Cloud, making it accessible via a simple web link.


🎯 Results
The model achieves high accuracy on the test set and provides real-time predictions through an intuitive user interface.
