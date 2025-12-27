
# 💰 Salary Prediction App

**Live Demo:** [Salary Predictor](https://employee-salarie-predictor.streamlit.app/)

This is a Machine Learning web application designed to predict the estimated salary of data and tech professionals based on various parameters such as experience level, job title, company location, and company size.

The application is built using **Python** and **Streamlit** and utilizes a pre-trained regression model to perform real-time predictions.

## 🚀 Features

* **Interactive Web Interface:** User-friendly inputs to select job criteria.
* **Machine Learning Model:** Uses a trained regressor (`model.pkl`) for accurate predictions.
* **Data Preprocessing:** Automatically handles categorical data using pre-trained label encoders for consistent input formatting.
* **Real-time Results:** Instantly calculates estimated salary upon submitting details.

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Frontend:** Streamlit
* **Machine Learning:** Scikit-Learn
* **Data Handling:** Pandas, NumPy, Pickle

## 📂 Project Structure

Here is an overview of the files in this repository:

| File Name | Description |
| :--- | :--- |
| `app.py` | The main Streamlit application file containing the UI and prediction logic. |
| `model.pkl` | The trained Machine Learning model used for prediction. |
| `*_encoder.pkl` | Serialized encoders used to transform user inputs (e.g., Job Title, Company Size) into the numerical format the model understands. |
| `requirements.txt` | List of Python dependencies required to run the project. |
| `setup.sh` | Configuration script for deployment environments (e.g., Streamlit Cloud). |

## 💻 Installation & Setup

Follow these steps to run the application locally on your machine.

### 1. Clone the Repository
```bash
    git clone [https://github.com/chiruratnala/Salary-Predictior.git](https://github.com/chiruratnala/Salary-Predictior.git)
    cd Salary-Prediction
```

### 2.Create a Virtual Environment (Optional but Recommended)
 ```bash
  python -m venv venv
```
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
### 3. Install Dependencies
 ```bash

pip install -r requirements.txt
```

### 4. Run the Application
 ```bash

streamlit run app.py
```
The app will launch in your default browser at http://localhost:8501.

### 🧠 How It Works
Input: The user selects values for features like Job Title, Experience Level, Employee Residence, etc., via the Streamlit interface.

Encoding: The app loads the specific .pkl encoder files (e.g., job_title_encoder.pkl) to convert these text inputs into numbers.

Prediction: The processed data is fed into model.pkl.

Output: The model returns a predicted salary value, which is displayed to the user.

### ☁️ Deployment
This project includes a setup.sh file, making it ready for deployment on platforms like Streamlit Cloud.

Push your code to this GitHub repository.

Log in to Streamlit Cloud.

Connect your repository (chiruratnala/Salary-Predictior) and select app.py as the main file.

Click Deploy!

### 🤝 Contributing
Contributions are welcome! If you have suggestions for improving the model accuracy or UI:

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Commit your changes.

Push to the branch and open a Pull Request.

## Author 

**Chiru Ratnala**

**GitHub:** https://github.com/chiruratnala
