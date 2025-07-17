# Professional Loan Prediction Web Application

## Overview
This project is a professional Flask-based web application for predicting loan approval. It features user authentication (signup/login/logout), model integration, and a visually appealing, consistent UI. User data is securely stored in a JSON file for persistence.

## Features
- **User Authentication:** Signup, login, and logout functionality with session management.
- **Persistent User Storage:** User details are saved in `app/users.json`.
- **Loan Prediction:** Integrates a trained machine learning model (`LoanPred.pkl`) to predict loan approval using five key features.
- **Modern UI:** Responsive design using Bootstrap and custom CSS, with a background image and clean card layout.
- **Error Handling:** User-friendly messages for invalid login, duplicate signup, and prediction errors.

## File Structure
```
Loanpredictions/
│
├── app/
│   ├── __init__.py           # Flask app initialization
│   ├── routes.py             # Main prediction routes
│   ├── auth.py               # Authentication routes and logic
│   ├── users.json            # Persistent user data storage
│   ├── templates/
│   │   ├── index.html        # Main prediction page
│   │   ├── login.html        # Login page
│   │   ├── signup.html       # Signup page
│   └── static/
│       ├── style.css         # Custom styles
│       ├── loanprdimg.jpg    # Background image
│       └── ...               # Other static assets
├── run.py                    # App entry point
└── LoanPred.pkl              # Trained ML model
```

## How It Works
1. **User Signup/Login:**
   - New users register via the signup page. Details are saved in `users.json`.
   - Existing users log in; sessions are managed for secure access.
2. **Loan Prediction:**
   - Users enter five features: Income, Credit Score, Loan Amount, DTI Ratio, Employment Status.
   - The app loads the trained model and returns a prediction result.
3. **UI/UX:**
   - Consistent styling across all pages.
   - Background image and card layout for a professional look.

## Setup Instructions
1. **Clone the repository** and navigate to the project folder.
2. **Install dependencies:**
   ```bash
   pip install flask scikit-learn
   ```
3. **Add your trained model:** Place `LoanPred.pkl` in the project root.
4. **Run the app:**
   ```bash
   python run.py
   ```
5. **Access the app:** Open your browser and go to `http://localhost:5000`.

## Customization
- **Background Image:** Replace `static/loanprdimg.jpg` with your preferred image.
- **Model:** Update `LoanPred.pkl` with your own trained model as needed.

## Security Note
- Passwords are stored in plain text in `users.json` for demonstration purposes. For production, use password hashing and a secure database.

## License
This project is for educational and demonstration purposes.
