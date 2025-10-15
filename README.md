# AI-Scam-Shield-Scam-Message-Detection
AI Scam Shield is a beginner-friendly Python project that detects whether a text message is a scam (fraudulent) or safe. The project leverages Machine Learning (Logistic Regression) along with TF-IDF Vectorization to classify messages. Users can input any message and get an instant prediction, making it a useful prototype for fraud prevention awareness.

Features:

Classifies messages as Scam or Safe

Simple user input interface

Uses Python, Pandas, and Scikit-learn

Easy to expand with larger datasets for better accuracy

Beginner-friendly and suitable for ideathons or learning ML concepts

How It Works:

Load a labeled dataset of messages (Scam or Safe) using Pandas

Convert text messages into numeric features using TF-IDF Vectorizer

Train a Logistic Regression model on the dataset

Take user input and predict if the message is Scam or Safe

Display the prediction along with a warning or safe message
