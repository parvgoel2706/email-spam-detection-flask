# 📧 Email Spam Detection System

## 👨‍💻 Developed By

**Parv Goel**\
B.Tech CSE -- Final Year

------------------------------------------------------------------------

## 📌 Project Overview

The **Email Spam Detection System** is a full-stack web application
developed to classify emails as **Spam** or **Ham (Not Spam)** using
Machine Learning techniques.

This system integrates:

-   A **Flask-based backend**
-   A responsive **HTML/CSS/JavaScript frontend**
-   A **MySQL database** for storing user data and email history
-   A trained **Machine Learning model** built using Scikit-Learn

The project demonstrates practical implementation of Natural Language
Processing (NLP) and supervised learning for real-world spam filtering.

------------------------------------------------------------------------

## 🎯 Objectives

-   Detect spam emails using Machine Learning\
-   Build a complete web-based application (Frontend + Backend)\
-   Implement user authentication and dashboard functionality\
-   Store classified emails in a database\
-   Deploy and showcase a real-world ML application

------------------------------------------------------------------------

## 🚀 Features

-   ✅ User Registration & Login System\
-   ✅ Real-time Email Classification\
-   ✅ Spam / Ham Prediction\
-   ✅ User Dashboard with Email History\
-   ✅ Machine Learning Model Integration\
-   ✅ Database Storage using MySQL

------------------------------------------------------------------------

## 🛠️ Technologies Used

### 🔹 Backend

-   Python\
-   Flask

### 🔹 Frontend

-   HTML\
-   CSS\
-   JavaScript

### 🔹 Database

-   MySQL

### 🔹 Machine Learning

-   Scikit-Learn\
-   Natural Language Processing (NLP)\
-   CountVectorizer / TF-IDF\
-   Multinomial Naive Bayes

------------------------------------------------------------------------

## ⚙️ System Architecture

1.  User enters email text in the web interface.\
2.  The backend preprocesses the text.\
3.  Text is converted into numerical features using vectorization.\
4.  The trained ML model predicts Spam or Ham.\
5.  Result is displayed instantly.\
6.  Email data is stored in MySQL database.

------------------------------------------------------------------------

## 📦 Installation & Setup

### 1️⃣ Clone the Repository

``` bash
git clone https://github.com/parvgoel2706/email-spam-detection.git
cd email-spam-detection
```

### 2️⃣ Create Virtual Environment

``` bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install Required Packages

``` bash
pip install -r requirements.txt
```

Or manually:

``` bash
pip install flask nltk mysql-connector-python scikit-learn pandas numpy
```

### 4️⃣ Setup MySQL Database

``` sql
CREATE DATABASE smc;
USE smc;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    full_name VARCHAR(255) NOT NULL,
    username VARCHAR(255) UNIQUE NOT NULL,
    email VARCHAR(255) UNIQUE NOT NULL,
    phone VARCHAR(15) NOT NULL,
    password VARCHAR(255) NOT NULL
);
```

### 5️⃣ Run the Application

``` bash
python app.py
```

Open in browser:

    http://127.0.0.1:5000/

------------------------------------------------------------------------

## 📊 Machine Learning Model

The spam detection model is built using:

-   Text preprocessing (cleaning, tokenization)\
-   Feature extraction using vectorization\
-   Multinomial Naive Bayes classifier\
-   Model serialization using Pickle

The model is trained on labeled spam datasets and achieves good accuracy
for binary classification.

------------------------------------------------------------------------

## 🌍 Deployment

The application can be deployed using:

-   Render\
-   Railway\
-   PythonAnywhere

Deployment-ready with minor configuration changes.

------------------------------------------------------------------------

## 📚 Learning Outcomes

Through this project, I gained practical knowledge of:

-   Flask Web Development\
-   Database Integration with Python\
-   Machine Learning model training & deployment\
-   Text preprocessing & NLP\
-   End-to-end ML web application development

------------------------------------------------------------------------

## 📜 License

This project is developed for academic purposes (Minor Project -- B.Tech
CSE).
