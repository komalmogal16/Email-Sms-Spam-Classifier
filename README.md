# 📧 Email/SMS Spam Classifier with MLOps

Welcome to the **Email/SMS Spam Classifier** repository! This project demonstrates a machine learning model designed to classify emails or SMS messages as either spam or not spam. It incorporates MLOps principles, Docker for containerization, GitHub Actions for CI/CD, and deployment on Render.

## 📖 Introduction

This repository showcases an Email/SMS Spam Classification system using machine learning. The project integrates MLOps best practices with Docker for consistent environment management, GitHub Actions for CI/CD, and deployment on Render for live usage.

---

## 🧠 What This Project Does

- Takes user input (email or SMS text)
- Cleans and transforms the text using **TF-IDF Vectorizer**
- Predicts whether the message is **Spam** or **Not Spam** using **Multinomial Naive Bayes**
- Displays the result on a clean web interface

---

## 🛠 Technologies & Concepts Used

- **Python** – Programming language for ML and backend  
- **Flask** – Web framework to serve the model  
- **Scikit-learn** – For machine learning model and TF-IDF vectorization  
- **Docker** – Containerizes the application for consistent environment  
- **Render** – Cloud platform to deploy the app  
- **GitHub Actions** – Automates CI/CD workflows  
- **MLOps** – End-to-end lifecycle management for ML  

---

## 🔍 Project Topics Covered

- **Machine Learning Models**: Multinomial Naive Bayes trained on SMS spam dataset  
- **Natural Language Processing (NLP)**: TF-IDF Vectorizer used for text transformation  
- **Model Evaluation**: Accuracy and performance tested using train-test split and confusion matrix  
- **MLOps**: Model versioning, reproducibility, and CI/CD pipeline implementation  
- **Docker**: App containerization using Dockerfile for portability  
- **CI/CD**: Automated deployment using GitHub Actions workflows  
- **Render**: Live deployment through Render cloud platform  

---

## 🧠 Machine Learning Workflow

1. Collected and cleaned the SMS Spam Collection Dataset  
2. Preprocessed text data using regular expressions and tokenization  
3. Transformed text into vectors using **TF-IDF**  
4. Trained a **Multinomial Naive Bayes** classifier using Scikit-learn  
5. Serialized the model and vectorizer using `pickle`  
6. Built a user-friendly interface using **Flask**  
7. Created a **Dockerfile** to containerize the application  
8. Pushed the app to **GitHub** and set up **CI/CD** with **GitHub Actions**  
9. Deployed the final application on **Render**  

---


**Live Demo** : [Click here](https://email-sms-spam-classifier-im3c.onrender.com/)
