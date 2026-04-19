🧠 Birth Weight Predictor

A Machine Learning-powered web application that predicts the birth weight of a newborn using maternal and health-related features. This project demonstrates an end-to-end data analytics workflow, from data preprocessing to model deployment.

📌 Project Overview

Birth weight is a crucial indicator of neonatal health. This project uses machine learning techniques to analyze maternal and medical factors and predict birth weight, enabling early risk identification and better decision-making.

🚀 Key Highlights
End-to-end ML pipeline implementation
Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
Feature engineering and model building
Web-based deployment using Flask
Real-time prediction through user input
🛠️ Tech Stack
Language: Python
Libraries: Pandas, NumPy, Scikit-learn
Visualization: Matplotlib, Seaborn
Web Framework: Flask
Tools: Jupyter Notebook, Git, GitHub
📊 Workflow
Data Collection
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Model Training & Evaluation
Model Deployment (Flask Web App)
📂 Project Structure
Birth_Weight_Predictor/
│
├── app.py                 # Main Flask application
├── model.pkl              # Trained machine learning model
├── requirements.txt       # Project dependencies
│
├── templates/             # HTML files for UI
│   └── index.html
│
├── static/                # CSS, JS, images
│   └── style.css
│
├── notebooks/             # Jupyter notebooks (EDA & modeling)
│
└── README.md
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/jha-kuldeep/Birth_Weight_Predictor.git
cd Birth_Weight_Predictor
2. Create virtual environment (recommended)
python -m venv venv
venv\Scripts\activate     # On Windows
3. Install dependencies
pip install -r requirements.txt
4. Run the application
python app.py
5. Open in browser
http://127.0.0.1:5000/
📈 Model Details
Algorithm Used: (Update this — e.g., Linear Regression / Random Forest)
Performance Metrics:
R² Score: (add your value)
MAE: (add your value)
RMSE: (add your value)
🎯 Features
User-friendly web interface
Real-time predictions
Data-driven insights
Lightweight and efficient model
📸 Screenshots

<img width="743" height="437" alt="image" src="https://github.com/user-attachments/assets/1d1790bd-9301-463a-9e60-11aa2b032f5b" />


💡 Future Improvements
Hyperparameter tuning for better accuracy
Deploy on cloud (AWS / Render / Railway)
Add more features for prediction
Improve UI/UX
👨‍💻 Author

Kuldeep Jha

GitHub: https://github.com/jha-kuldeep
LinkedIn: www.linkedin.com/in/kuldeep-jha-b3517b316
⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

🔧 Quick Fix (if your project differs)

If you used Streamlit, replace:

python app.py

with:

streamlit run app.py
If your model file name is different (e.g., birth_model.pkl), update that in the structure.
