📌 Overview
The Churn Prediction App is a machine learning-based web application built using Streamlit. It allows users to predict customer churn based on various input features such as age, tenure, gender, and monthly charge. The model is trained on a dataset, and predictions are made using a pre-trained machine learning model.

🚀 Features
User-friendly web interface built with Streamlit

Takes inputs for Age, Tenure, Gender, and Monthly Charge

Uses a pre-trained model to predict churn

Displays the prediction as "Yes" (Churn) or "No" (Not Churn)

Interactive UI with balloons animation on prediction

🏗️ Tech Stack
Python

Streamlit (for web interface)

Joblib (for model loading)

NumPy (for array operations)

Scikit-learn (for model preprocessing)

📂 Project Structure
      Churn-Prediction-App  
│── 📜 app.py                             # Streamlit application  
│── 📜 notebook.ipynb                     # Jupyter Notebook (Model Training & Analysis)  
│── 📜 scaler.pkl                         # Pre-trained Scaler  
│── 📜 model.pkl                          # Pre-trained Machine Learning Model  
│── 📜 customer_churn_data.csv            # dataset  
🔧 Setup Instructions


Clone the repository
git clone <repository_link>
cd Churn-Prediction-App


Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Mac/Linux
venv\Scripts\activate  # On Windows


Install dependencies
pip install -r requirements.txt


Run the Streamlit app
streamlit run app.py


📊 How It Works
The user enters age, tenure, gender, and monthly charge in the web app.

The input data is scaled using a pre-trained scaler (scaler.pkl).

The pre-trained machine learning model (model.pkl) predicts churn.

The result is displayed as "Yes" (Customer will churn) or "No" (Customer will not churn).


🤖 Model Details
The Jupyter Notebook (notebook.ipynb) contains:

Data preprocessing

Model training

Feature engineering

Performance evaluation


Installation:
Once you've created the file, install the dependencies using:
pip install -r requirements.txt
