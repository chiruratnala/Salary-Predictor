promise.

# 💰 Salary Prediction App

**Live Demo:** https://employee-salarie-predictor.streamlit.app/

The **Salary Prediction App** is a Machine Learning–based web application designed to predict the estimated salary of data and tech professionals based on parameters such as experience level, job title, company location, and company size.

The application is built using **Python** and **Streamlit**, and it uses a pre-trained regression model to perform real-time salary predictions.

---

## 🚀 Features

- Interactive web interface with user-friendly inputs  
- Machine learning regression model for salary prediction  
- Automatic preprocessing of categorical data using encoders  
- Real-time salary prediction  

---

## 🛠️ Tech Stack

- Language: Python 3.x  
- Frontend: Streamlit  
- Machine Learning: Scikit-learn  
- Data Handling: Pandas, NumPy  
- Model Storage: Pickle  

---

## 📂 Project Structure



Salary-Predictior/
│
├── app.py
├── model.pkl
├── experience_level_encoder.pkl
├── job_title_encoder.pkl
├── employment_type_encoder.pkl
├── company_location_encoder.pkl
├── company_size_encoder.pkl
├── employee_residence_encoder.pkl
├── requirements.txt
├── setup.sh
└── README.md


---

## 💻 Installation & Setup

Follow these steps to run the application locally.

### Step 1: Clone the Repository

```bash
git clone https://github.com/chiruratnala/Salary-Predictior.git
cd Salary-Predictior

Step 2: Create a Virtual Environment (Optional but Recommended)
python -m venv venv


Activate the environment:

Windows

venv\Scripts\activate


macOS / Linux

source venv/bin/activate

Step 3: Install Dependencies
pip install -r requirements.txt

Step 4: Run the Application
streamlit run app.py


The app will be available at:

http://localhost:8501

🧠 How It Works

Input
Users select job-related details through the Streamlit interface.

Encoding
Categorical inputs are transformed using pre-trained encoder files (*.pkl).

Prediction
The processed data is passed to the trained model (model.pkl).

Output
The predicted salary is displayed instantly.

☁️ Deployment

This project is ready for deployment on Streamlit Cloud.

Deployment Steps

Push the project to GitHub

Log in to Streamlit Cloud

Connect the repository: chiruratnala/Salary-Predictior

Select app.py as the main file

Click Deploy
