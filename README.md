## End to End Machine Learning Project

# 🎓 Student Performance Prediction System

An end-to-end Machine Learning project that predicts student academic performance using demographic and educational attributes. The project demonstrates the complete ML lifecycle from data ingestion and preprocessing to model training, evaluation, deployment, and cloud hosting.

## 🚀 Project Overview

The objective of this project is to predict student academic performance based on various demographic and educational factors. The project follows a production-oriented approach by combining machine learning, software engineering, containerization, cloud deployment, and CI/CD practices.

The system allows users to input student information through a web interface and receive predicted performance scores in real time.

---

## 🏗️ Project Architecture

User Input
    │
    ▼
Flask Web Application
    │
    ▼
Prediction Pipeline
    │
    ▼
Preprocessing Pipeline
    │
    ▼
Trained Machine Learning Model
    │
    ▼
Prediction Output

---

## ✨ Features

* End-to-end machine learning workflow
* Data ingestion and preprocessing pipeline
* Feature engineering and transformation
* Training and comparison of multiple regression models
* Hyperparameter tuning and model selection
* Real-time prediction interface
* Flask web application
* Docker containerization
* AWS deployment
* GitHub Actions CI/CD workflow
* Modular and scalable project structure

---

## 🛠️ Technology Stack

### Programming Language
* Python

### Machine Learning
* Scikit-Learn
* CatBoost
* XGBoost

### Data Processing
* Pandas
* NumPy

### Visualization
* Matplotlib
* Seaborn

### Web Framework
* Flask

### Cloud & Deployment
* AWS Elastic Beanstalk
* Docker

### DevOps & Version Control
* Git
* GitHub
* GitHub Actions

---

## 📂 Project Structure
student-performance-ml-system
│
├── .github/
│   └── workflows/
│
├── .ebextensions/
│
├── artifacts/
│
├── notebooks/
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   ├── train_pipeline.py
│   │   └── predict_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│
├── static/
│
├── application.py
├── Dockerfile
├── requirements.txt
├── setup.py
└── README.md
```

---

## 📊 Machine Learning Workflow

### 1. Data Ingestion
* Load raw student performance data
* Split training and testing datasets
* Store processed datasets

### 2. Data Transformation
* Handle categorical variables
* Feature encoding
* Data preprocessing using pipelines
* Feature scaling

### 3. Model Training
Multiple regression algorithms are trained and evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* AdaBoost Regressor
* XGBoost Regressor
* CatBoost Regressor

### 4. Model Evaluation
Models are evaluated and compared using performance metrics to identify the best-performing model.

### 5. Prediction Pipeline

A dedicated prediction pipeline processes user inputs and generates performance predictions through the deployed application.

---

## 🌐 Deployment

The application is designed for cloud deployment and includes:

### Docker

* Containerized application for consistent deployment

### AWS Elastic Beanstalk

* Cloud deployment configuration
* Scalable hosting environment

### GitHub Actions

* Automated CI/CD workflow
* Streamlined deployment process

---

## ▶️ Running the Project Locally

### Clone the Repository

```bash
git clone https://github.com/Anicodes18/student-performance-ml-system.git
cd student-performance-ml-system
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python application.py
```

---

## 🐳 Running with Docker

Build Image:

```bash
docker build -t student-performance .
```

Run Container:

```bash
docker run -p 5000:5000 student-performance
```

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:
* Machine Learning model development
* Data preprocessing and feature engineering
* End-to-end ML pipeline creation
* Flask application development
* Docker containerization
* AWS cloud deployment
* CI/CD implementation using GitHub Actions
* Production-oriented ML project structure

---

## 👨‍💻 Author

### Aniket Rane

Data Analyst | Data Science & Machine Learning Enthusiast

* MSc Data Analytics
* MSc Statistics

📫 LinkedIn: https://www.linkedin.com/in/aniket-rane

---

⭐ If you found this project useful, consider giving it a star!

