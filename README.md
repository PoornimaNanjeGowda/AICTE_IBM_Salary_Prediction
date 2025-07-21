

# 💼 AICTE IBM Employee Salary Prediction

An AI-powered web application that predicts employee salaries based on job role, education, experience, and gender. This project was developed under the **AICTE–IBM Internship Program** using machine learning, and offers a simple and intuitive interface to analyze and visualize salary trends.

![Salary Prediction]
(https://github.com/PoornimaNanjeGowda/AICTE_IBM_Salary_Prediction)

---

## 🚀 Live App

👉 (# 💼 AICTE IBM Employee Salary Prediction

An AI-powered web application that predicts employee salaries based on job role, education, experience, and gender. This project was developed under the **AICTE–IBM Internship Program** using machine learning, and offers a simple and intuitive interface to analyze and visualize salary trends.

![Salary Prediction]

(https://github.com/PoornimaNanjeGowda/AICTE_IBM_Salary_Prediction)

---

## 🚀 Live App

👉 (https://salary-prediction-app-by-poornima.streamlit.app)  

---

## ✨ Features

- 🎯 Predict **Monthly** and **Annual Salary**
- 📈 Display salary **growth trends over years of experience**
- 📊 Interactive **line charts**, **scatter plots**, and **gauge meters**
- 📁 Upload custom CSV datasets for predictions
- 🧠 Auto-detect and match similar column names (e.g. `sex` = `gender`)
- 📂 Built-in **admin dashboard** for resume matches and salary stats
- 🧾 Editable **resume builder**
- 🎯 Job recommendation engine based on skills in resume

---

## 🛠️ Tech Stack

| Tool              | Purpose                            |
|-------------------|------------------------------------|
| Python 3.11+       | Core programming language         |
| Streamlit         | Web interface                      |
| scikit-learn      | Machine Learning model             |
| pandas & NumPy    | Data manipulation                  |
| plotly            | Interactive visualizations         |
| joblib            | Model serialization                |
| Git + GitHub      | Version control & collaboration    |

---

## 📂 Project Structure

AICTE_IBM_Salary_Prediction/
├── app.py # Streamlit app
├── best_model.pkl.gz # Compressed ML model
├── trained_columns.pkl # List of columns used for training
├── label_encoders.pkl # Label encoders for categorical features
├── AICTE_IBM_Employee__Salary_predication.ipynb # Model building notebook
├── README.md # Project documentation
└── assets/
├── screenshot.png
└── growth_chart.png

---

## 📈 Visualizations

| Chart Type        | Description                                         |
|-------------------|-----------------------------------------------------|
| 📈 Line Chart     | Shows salary progression over 0–20 years experience|
| 📂 Custom Dataset | Analyzes trends from uploaded files                |


🔧 Project Setup Instructions

✅ 1. Pre-requisites
Make sure you have the following installed on your system:

Python 3.8+
Git
pip (Python package manager)
(Optional) virtualenv


📥 2. Clone the Repository
Open your terminal or command prompt and run:

git clone https://github.com/PoornimaNanjeGowda/AICTE_IBM_Salary_Prediction.git
cd AICTE_IBM_Salary_Prediction


📦 3. Set Up a Virtual Environment (Recommended)

# Create virtual environment
python -m venv venv

# Activate the virtual environment
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate


📚 4. Install Dependencies
Make sure to install required packages. If requirements.txt is not present, install manually:

pip install streamlit scikit-learn pandas numpy plotly joblib
Or if requirements.txt exists:

pip install -r requirements.txt


🚀 5. Run the Streamlit App

streamlit run app.py
After a few seconds, the app will open in your default web browser at:
http://localhost:8501


💡 Optional Tips
To update from GitHub later:

git pull origin main
To push changes (after setting identity):

git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git add .
git commit -m "Your update message"
git push origin main
