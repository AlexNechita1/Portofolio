# Portofolio
This space showcases a curated collection of my academic, personal, and collaborative projects developed throughout my journey as an Information Technology student.

## 🎮 Sentiment Classification of Steam Reviews using PySpark & Big Data

**Description:** This project focuses on classifying user reviews from the Steam platform using Big Data processing and machine learning techniques. The goal was to evaluate the performance of multiple classifiers in a distributed computing environment. I implemented and compared three machine learning models — Naive Bayes, Support Vector Machine (SVM), and Random Forest — to classify Steam user reviews into three sentiment categories: positive, neutral, and negative. The analysis was conducted in both local and distributed environments to highlight the scalability and efficiency of Big Data tools.

**Technologies & Tools Used :**
- Kaggle: Source of the user reviews dataset
- PySpark: For distributed data processing and machine learning model implementation
- Python: Core programming language for data preprocessing, modeling, and evaluation
- Google Cloud Platform (GCP): Cloud infrastructure for running distributed Spark jobs
- Jupyter Notebook: For exploratory data analysis and model development

## 🛡️ Phishing Website Detection using Machine Learning

**Description:** This project tackles the problem of automated phishing website detection using a variety of machine learning algorithms. The goal is to classify websites as legitimate or phishing based on their attributes and behaviors. I used the publicly available "Phishing Websites" dataset from the UCI Machine Learning Repository. After preprocessing the data, we trained and optimized multiple models, ranging from classic to advanced classifiers. These include: Logistic Regression, Support Vector Machine (SVM), k-Nearest Neighbors (KNN), Random Forest, Gradient Boosting,Multi-Layer Perceptron (MLP). The models were evaluated using key metrics such as F1-score, ROC AUC, and cross-validation scores.

**Technologies & Tools Used:**
- Python: For all development and modeling
- scikit-learn (sklearn): Machine learning framework for model implementation and evaluation
- Google Colab: Cloud-based development environment for fast experimentation and collaboration
- Pandas / NumPy: For data handling and processing
- Matplotlib / Seaborn: For visualizations and metric analysis

## 💬 MatchMate – Microservices Architecture Web App

**Link to Demo:** https://drive.google.com/file/d/1paA5UbmhD5yNbLDHVljPDgMNWdVDRS-y/view?usp=sharing

**Description:** MatchMate is a microservices-based web application that connects users based on their gaming preferences, availability, and play styles. The platform is designed to deliver a scalable, modular, and cloud-native experience using Microsoft Azure and Docker containers.
The application is composed of three independent, containerized services:
- 🧾 User Service: Handles registration, authentication, and user profiles
- 🎯 Matchmaking Service: Calculates compatibility scores and manages friend requests
- 💬 Chat Service: Enables real-time messaging, stores feedback and chat history
All services communicate through RESTful APIs and are deployed via Azure Container Apps. Compatibility is determined by analyzing user interests, gaming behavior, and mutual feedback.

**Technologies & Tools Used:**
- Node.js & JavaScript: Backend service development
- Docker: Containerization for modular deployment
- Azure Container Apps: Cloud-native hosting and scaling
- Azure SQL / MSSQL: Cloud-hosted relational database
- REST API: Service-to-service communication

## 🎬 MovieGram – Social Movie Recommendation App

**Description:** MovieGram is a mobile application that combines movie discovery with social networking — think of it as Instagram for movie enthusiasts. Built in Java using Android Studio, MovieGram allows users to explore personalized movie recommendations and interact with a community of fellow cinephiles.
Users can:
- 📽️ Browse a custom movie database, populated via the IMDb API
- ⭐ Receive smart movie recommendations based on preferences and viewing history
- 📝 Create reviews and social posts for movies they've watched
- 👤 Customize their profile with avatars, bios, and favorite genres
- 🤝 Add friends and view their activity, reviews, and posts
- 🔍 Use the search function to explore trending or specific titles
- 🗄️ Enjoy a smooth UX through local database integration and synced API data

The app uses local storage for fast access and supports syncing with IMDb data to ensure users get fresh and accurate content. The goal is to create a scalable and social platform that enhances movie discovery through personalization and community interaction.

**Technologies Used:**
- Java: Main programming language
- Android Studio: Development environment
- IMDb API: External movie metadata
- Firebase: Data storage
