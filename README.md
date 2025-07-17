# 💰 Loan Approval Prediction System (End-to-End ML + Web App)

Welcome to my third end-to-end Machine Learning project! This repository contains a complete implementation of a **Loan Approval Prediction System** – from data preprocessing and model training to deploying the model as a simple, functional **Flask web application**.

---

## 🚀 Project Overview

This project was designed to simulate a real-world use case in financial services – predicting whether a loan application should be approved based on applicant details.

**Key Features:**
- Data cleaning, visualization, and preprocessing
- ML model development using Scikit-learn
- Model evaluation and saving using Pickle
- Flask web app for interactive loan predictions
- Simple login/signup user system with JSON

---

## 🛠️ Tech Stack

| Purpose                | Tools Used                      |
|------------------------|----------------------------------|
| Data Handling          | Pandas, NumPy                   |
| Visualization          | Matplotlib, Seaborn             |
| Machine Learning       | Scikit-learn                    |
| Model Serialization    | Pickle                          |
| Web Framework          | Flask                           |
| Frontend (Simple UI)   | HTML, CSS                       |
| User Data Management   | JSON                            |
| Development Environment| Jupyter Notebook, VS Code       |

---

## 📂 Project Structure

```bash
Loan-Prediction-ML-Flask-App/
│
├── static/                     # CSS, image files (if needed)
├── templates/                  # HTML templates (home, login, signup, predict)
│   ├── home.html
│   ├── login.html
│   ├── signup.html
│   └── predict.html
│
├── loan_model.pkl              # Trained ML model saved with Pickle
├── user_data.json              # JSON file to store login/signup info
├── app.py                      # Flask app to handle backend logic
├── loan_prediction.ipynb       # Jupyter notebook for EDA & model training
├── requirements.txt            # Required libraries
└── README.md                   # Project documentation
```

📊 Dataset
The dataset was sourced from Kaggle:
Loan Prediction Dataset
 

Target: Loan_Status (Yes/No)
 🔍 Project Workflow
1. Data Preprocessing
Handled missing values using mean/mode imputation

Label-encoded categorical variables

Explored feature relationships using heatmaps and box plots

2. Model Training
Used Logistic Regression and Decision Tree classifiers

Split data using train_test_split

Evaluated using the accuracy score and the confusion matrix

3. Model Serialization
Final model saved as loan_model.pkl using Pickle

4. Web Integration
Flask is used to create web routes

HTML templates for UI

JSON for user login/signup functionality

🧪 How to Run the Project Locally
bash
Copy
Edit
# 1. Clone the repository
git clone https://github.com/your-username/loan-prediction-app.git
cd loan-prediction-app

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

# 3. Install requirements
pip install -r requirements.txt

# 4. Run the Flask app
python app.py

# 5. Open browser and visit:
http://127.0.0.1:5000
   
Target: Loan_Status (Yes/No)
 
HTML templates for UI

JSON for user login/signup functionality
 
🙌 Acknowledgements
Kaggle for providing the dataset

Flask for backend framework

Scikit-learn for machine learning models

 

⭐️ Show Your Support
If you found this project helpful, feel free to:

⭐️ Star this repository

🍴 Fork it

🤝 Open a pull request

🗣️ Share with your peers

🧠 Final Note
This project taught me a lot about combining Machine Learning and software deployment. If you're starting out in data science, I highly recommend building projects like this — they challenge you, teach you, and boost your confidence in applying what you learn.

Keep exploring! Keep building!
💼 Portfolio 
 
