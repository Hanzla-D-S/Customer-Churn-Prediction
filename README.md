🚀 Credit Card Customer Churn Prediction Using Deep Learning
📌 Overview
This project focuses on predicting customer churn in the banking sector using deep learning. We preprocess the dataset, perform feature engineering, and apply a Neural Network model to classify whether a customer will churn or not.

📂 Dataset
The dataset used in this project is from Kaggle:
🔗 Credit Card Customer Churn Prediction

It contains details such as:

Customer demographics
Account balance
Credit score
Transaction history
Churn status
🛠️ Technologies Used
Python 🐍
Pandas & NumPy – Data processing & manipulation
Scikit-learn – Data preprocessing & splitting
TensorFlow & Keras – Deep learning model
Matplotlib – Visualization
📊 Data Preprocessing
✔ Handling missing values & duplicates
✔ One-hot encoding categorical features
✔ Feature scaling using StandardScaler
✔ Splitting data into training & testing sets

🤖 Model Architecture
A fully connected Neural Network with:

Input layer – 11 neurons (features)
Hidden layers – 2 layers (each with 11 neurons & ReLU activation)
Output layer – 1 neuron (Sigmoid activation for binary classification)
Model Compilation:
Loss Function: Binary Crossentropy
Optimizer: Adam
Metric: Accuracy
🚦 Training the Model
The model is trained for 100 epochs, using 20% validation split to track performance.

📉 Loss & Accuracy Graphs:

Training vs Validation Loss
Training vs Validation Accuracy
📌 Results
✅ Model evaluation using Accuracy Score
✅ Predictions using the trained model

📈 Visualization
Plots for:
📊 Loss vs Validation Loss
📊 Accuracy vs Validation Accuracy

