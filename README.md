# 🎓 EduPredict AI - Student Performance Prediction System

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Flask](https://img.shields.io/badge/Framework-Flask-black)

## 📌 Project Overview

**EduPredict AI** is an end-to-end Machine Learning application that predicts student academic performance based on various demographic and academic factors.

The system uses Machine Learning algorithms to analyze student information such as gender, parental education, lunch category, test preparation status, reading score, and writing score to predict performance outcomes.

The trained ML model is integrated with a **Flask web application** that allows users to enter student details and receive real-time predictions.

---

## 🚀 Features

- ✅ Machine Learning-based student performance prediction
- ✅ End-to-end ML pipeline implementation
- ✅ Data preprocessing and feature engineering
- ✅ Model training and evaluation
- ✅ Flask-based web application
- ✅ Real-time prediction system
- ✅ Modular project structure
- ✅ Easy deployment and scalability

---

# 🏗️ Project Structure

```
EduPredict-AI
│
├── artifacts
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── src
│   │
│   ├── components
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline
│   │   └── prediction_pipeline.py
│   │
│   └── utils
│
├── templates
│   ├── index.html
│   └── home.html
│
├── app.py
├── requirements.txt
└── setup.py
```

---

# 🧠 Machine Learning Workflow

The project follows a complete machine learning lifecycle:

```
Dataset
   |
   ↓
Data Collection
   |
   ↓
Data Cleaning
   |
   ↓
Feature Engineering
   |
   ↓
Data Transformation
   |
   ↓
Model Training
   |
   ↓
Model Evaluation
   |
   ↓
Model Deployment
   |
   ↓
Prediction
```

---

# 📊 Dataset Features

The model uses the following input features:

| Feature | Description |
|---------|-------------|
| Gender | Student gender |
| Race/Ethnicity | Student background category |
| Parental Education | Parent education qualification |
| Lunch | Lunch category |
| Test Preparation Course | Preparation course completion status |
| Reading Score | Reading marks |
| Writing Score | Writing marks |

---

# 🤖 Machine Learning Algorithms

The following algorithms are trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
- CatBoost Regressor

The best-performing model is selected and integrated into the prediction pipeline.

---

# 🛠️ Technology Stack

## Programming Language
- Python

## Machine Learning
- Scikit-learn
- XGBoost
- CatBoost

## Data Processing
- Pandas
- NumPy

## Data Visualization
- Matplotlib
- Seaborn

## Web Framework
- Flask

## Model Serialization
- Dill / Pickle

---

# ⚙️ Installation and Setup

## Clone the Repository

```bash
git clone https://github.com/Shayaritd/ML-Project.git
```

## Navigate to Project Folder

```bash
cd ML-Project
```

## Create Virtual Environment

```bash
python -m venv venv
```

Activate Virtual Environment:

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

---

## Install Required Libraries

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

Start the Flask server:

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000/
```

---

# 🔮 Prediction Flow

```
User Input
     |
     ↓
Flask Web Application
     |
     ↓
Data Preprocessing Pipeline
     |
     ↓
Trained Machine Learning Model
     |
     ↓
Student Performance Prediction
```

---

# 📸 Application Screenshots

Add screenshots of your application here:

```
screenshots/
│
├── home.png
└── prediction.png
```

Example:

```
![Home Page](screenshots/home.png)

![Prediction Page](screenshots/prediction.png)
```

---

# 📈 Future Enhancements

- Deploy application using AWS / Azure / Google Cloud
- Add student performance analytics dashboard
- Add authentication system
- Improve model accuracy using advanced algorithms
- Provide personalized learning recommendations
- Create REST API support

---

# 🤝 Contribution

Contributions are welcome.

Steps:

1. Fork this repository

2. Create a new branch:

```bash
git checkout -b feature-name
```

3. Commit changes:

```bash
git commit -m "Added new feature"
```

4. Push changes:

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 👨‍💻 Author

**Shayaritd**

GitHub:
https://github.com/Shayaritd

---

# 📄 License

This project is licensed under the MIT License.
