# Text-Classification-of-Spam-and-Harmful-Content-Using-Natural-Language-Processing-NLP-
Text Classification of Spam and Harmful Content Using Natural Language Processing is an AI project that detects and classifies spam and harmful text messages using NLP and machine learning. It applies text preprocessing, TF-IDF feature extraction, and a trained classifier, with a Python GUI and database support for real time prediction securely.!

📩 Text Classification of Spam and Harmful Content Using NLP
📌 Overview
This project is an Artificial Intelligence–based system designed to automatically detect and classify spam and harmful text messages using Natural Language Processing (NLP) and machine learning techniques. The system analyzes textual data and predicts whether a message is Spam or Ham (Legitimate) with high accuracy.

The project demonstrates a complete end-to-end AI pipeline, from data preprocessing and model training to deployment in a user-friendly graphical interface.

🎯 Objectives
To detect spam and harmful SMS messages automatically
To apply NLP techniques for text preprocessing and feature extraction
To train and evaluate a machine learning classification model
To integrate the trained model into a Python GUI application
To store prediction history using a database

⚙️ Features
Text preprocessing (cleaning, stopword removal, normalization)
TF-IDF feature extraction
Machine learning–based text classification
Real-time prediction through a GUI
User authentication (Admin / User)
Prediction history storage using SQLite
Dark and Light mode interface
High accuracy spam detection

🧠 Model & Techniques
Natural Language Processing (NLP)
TF-IDF Vectorization
Multinomial Naive Bayes Classifier
Supervised Machine Learning

🛠️ Technologies Used
Python
Scikit-learn
Pandas & NumPy
Tkinter (GUI)
SQLite
Joblib

📂 Project Structure
├── dataset/
│   └── SMSSpamCollection
├── model/
│   ├── spam_model.pkl
│   └── tfidf_vectorizer.pkl
├── gui/
│   └── app.py
├── database/
│   └── spam_system.db
├── README.md
