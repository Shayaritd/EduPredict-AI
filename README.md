# 🎓 Student Performance Prediction using Machine Learning

A Machine Learning based web application that predicts student performance using various academic and demographic factors. The project uses a trained ML model integrated with a Flask web application to provide real-time predictions through an interactive interface.

---

## 📌 Project Overview

Student performance depends on multiple factors such as:

- Student background
- Parental education level
- Lunch category
- Test preparation course
- Reading and writing scores

This project uses Machine Learning algorithms to analyze these factors and predict student performance. The trained model is deployed using Flask, allowing users to enter student information and receive predictions instantly.

---

## 🚀 Features

✅ Machine Learning based prediction system  
✅ Flask web application interface  
✅ Data preprocessing pipeline  
✅ Model training and evaluation  
✅ Real-time prediction  
✅ User-friendly HTML interface  
✅ Modular ML pipeline architecture  

---

## 🏗️ Project Architecture

```
ML-Project
│
├── artifacts
│   ├── Model files
│   └── Preprocessor files
│
├── src
│   │
│   ├── components
│   │   ├── Data Ingestion
│   │   ├── Data Transformation
│   │   └── Model Trainer
│   │
│   ├── pipeline
│   │   └── Prediction Pipeline
│   │
│   └── utils
│
├── templates
│   ├── index.html
│   └── home.html
│
├── app.py
├── application.py
├── requirements.txt
└── setup.py
```

---

## 🧠 Machine Learning Workflow

The project follows the complete ML lifecycle:

### 1. Data Collection
Student performance dataset is collected containing academic and personal attributes.

### 2. Data Preprocessing

Steps include:

- Handling missing values
- Feature encoding
- Feature transformation
- Data scaling

### 3. Model Training

Different ML algorithms are trained and evaluated.

Algorithms used:

- Linear Regression
- Decision Tree
- Random Forest
- XGBoost
- CatBoost

### 4. Model Evaluation

Models are compared using performance metrics to select the best-performing model.

### 5. Deployment

The trained model is integrated with Flask to provide predictions through a web interface.

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Machine Learning
- Scikit-learn
- CatBoost
- XGBoost

### Data Processing
- Pandas
- NumPy

### Visualization
- Matplotlib
- Seaborn

### Web Framework
- Flask

### Model Serialization
- Dill

---

## 📦 Installation and Setup

### Clone the repository

```bash
git clone https://github.com/Shayaritd/ML-Project.git
```

### Navigate into the project folder

```bash
cd ML-Project
```

### Create virtual environment

```bash
python -m venv venv
```

Activate environment:

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start Flask server:

```bash
python app.py
```

or

```bash
python application.py
```

The application will start on:

```
http://127.0.0.1:5000/
```

---

## 📊 Input Features

The model accepts:

| Feature | Description |
|---|---|
| Gender | Student gender |
| Race/Ethnicity | Student background group |
| Parental Education | Parent education level |
| Lunch | Lunch category |
| Test Preparation Course | Completed preparation course or not |
| Reading Score | Reading marks |
| Writing Score | Writing marks |

---

## 🔮 Prediction Flow

```
User Input
     |
     ↓
Flask Web Application
     |
     ↓
Data Transformation
     |
     ↓
ML Model
     |
     ↓
Prediction Result
```

---

## 📸 Application Screenshots

(Add screenshots here)

Example:

```
![Home Page](images/home.png)

![Prediction Page](images/prediction.png)
```

---

## 📈 Future Improvements

- Add more ML algorithms
- Improve prediction accuracy
- Deploy using AWS / Azure
- Add user authentication
- Add model performance dashboard
- Add REST API support

---

## 🤝 Contribution

Contributions are welcome!

Steps:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 👩‍💻 Author

**Shayaritd**

GitHub:
https://github.com/Shayaritd

---

## 📄 License

This project is open-source and available under the MIT License.
