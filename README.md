# Enhancing Password Security via Supervised Learning

## 📌 Project Overview

This project focuses on improving password security using supervised
machine learning techniques. Passwords are widely used for
authentication, but weak passwords make systems vulnerable to attacks.
The goal of this project is to analyze password patterns and classify
password strength using machine learning models.

The system predicts whether a password is strong or weak based on
patterns learned from a dataset. This helps users create more secure
passwords and reduces the risk of brute-force or dictionary attacks.

------------------------------------------------------------------------

## 🎯 Objectives

-   Analyze password patterns using machine learning.
-   Detect weak and strong passwords automatically.
-   Improve password security by predicting vulnerability.
-   Provide an intelligent system for password strength classification.

------------------------------------------------------------------------

## 🛠 Technologies Used

-   Python
-   Machine Learning
-   TF-IDF (Term Frequency -- Inverse Document Frequency)
-   Random Forest Classifier
-   Logistic Regression
-   Django (Web Framework)
-   SQLite Database

------------------------------------------------------------------------

## 📂 Project Modules

### 1️⃣ User Module

-   Users can register and login to the system.
-   Upload datasets for analysis.
-   Perform data preparation and cleaning.
-   Enter a password to check its strength.

### 2️⃣ Admin Module

-   Admin manages users and system data.
-   Admin can activate registered users.
-   Admin can load datasets and view results.

### 3️⃣ Prediction Module

-   User enters a password.
-   The system analyzes the password using trained ML models.
-   The system predicts password strength.

------------------------------------------------------------------------

## ⚙️ Methodology

1.  **Data Collection**
    -   Password dataset collected via web scraping.
2.  **Data Preprocessing**
    -   Handling missing values
    -   Data shuffling
    -   Feature extraction using TF-IDF.
3.  **Model Training**
    -   Dataset split into **80% training and 20% testing**.
4.  **Machine Learning Algorithms Used**
    -   Random Forest Classifier
    -   Logistic Regression
5.  **Model Evaluation**
    -   Random Forest achieved **94.22% accuracy**.
    -   Logistic Regression achieved **81% accuracy**.

------------------------------------------------------------------------

## 📊 Results

The machine learning models successfully classify password strength by
learning patterns in password data. Random Forest performed better than
Logistic Regression in terms of accuracy.

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Improve model accuracy with larger datasets.
-   Integrate deep learning models like RNN or LSTM.
-   Add real-time password strength suggestions.
-   Deploy the system as a web application.

------------------------------------------------------------------------

## 👩‍💻 Author

**Poojitha Nainaru**\
B.Tech -- Computer Science and Engineering\
Sree Rama Engineering College

Project Team: - Nainaru Poojitha - Nookala Madhuri - Jalla Akhila - K.
Padma Priya - Moravaneni Jahnavi

------------------------------------------------------------------------

## 📚 References

Research papers and studies related to password security, machine
learning, and authentication systems were used for developing this
project.
