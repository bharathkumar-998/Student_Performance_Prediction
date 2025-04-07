# 🎓 Student Performance Analysis & Prediction

Welcome to my data science project where I explore and analyze student performance data to build a machine learning model that predicts whether a student will pass based on their academic and demographic factors.

---

## 📁 Project Structure

C:/Users/bhara/Student_Performance_Prediction/ │ ├── Student_Performance_Prediction.ipynb # Main Jupyter Notebook ├── student_performance.csv # Dataset └── README.md # Project Overview

---

## 📊 Objective

This project aims to:

- Perform Exploratory Data Analysis (EDA) on student performance
- Engineer a new feature `average_score`
- Build a classification model to predict whether a student will **pass (score ≥ 60)** or **fail**
- Visualize key trends based on gender, test preparation, and more

---

## 🧠 About the Dataset

Each row in the dataset represents a student and includes:

- **gender**
- **race/ethnicity**
- **parental level of education**
- **lunch**
- **test preparation course**
- **math score**
- **reading score**
- **writing score**

---

## 📌 Key Steps

1. 📥 Load and clean the dataset  
2. 🛠 Feature Engineering (`average_score`, `pass`)  
3. 📊 Visualize insights using Seaborn & Matplotlib  
4. ⚙️ One-hot encode categorical features  
5. 🤖 Build Logistic Regression model  
6. 🧪 Evaluate performance with Accuracy & Classification Report  

---

## 🚀 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Results

The logistic regression model performs well in identifying students at risk, based on test scores and preparation. Accuracy and classification metrics provide insight into model performance.

---

## 🧪 How to Run This Project

1. Clone the repo:
```bash
git clone https://github.com/bharathkumar-998/Student_Performance_Prediction.git
cd Student_Performance_Prediction
Launch Jupyter Notebook:
jupyter notebook Student_Performance_Prediction.ipynb

👨‍💻 Author
Bharath Kumar Yandrapu
BTech 3rd Year - Data Science Student
📍 India
- 🔗 [GitHub Profile](https://github.com/bharathkumar-998)  
- 💼 [LinkedIn Profile](https://www.linkedin.com/in/bharath-kumar-yandrapu-05a8b0356)

