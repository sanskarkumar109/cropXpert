# 🌾 CropXpert - Crop Yield Prediction App

CropXpert is a machine learning-based application that predicts crop yield using various environmental and agricultural parameters. It comes with a user-friendly **Streamlit frontend** and a **FastAPI backend** that serves a trained model stored locally.

---

## 🧠 Features

- 🔍 Predict crop yield based on area, item, rainfall, temperature, and pesticide usage
- 📈 Streamlit UI for input and display
- ⚙️ FastAPI backend to handle ML predictions
- 🧠 Pre-trained Random Forest Regressor model with label encoders

---

## 🧰 Tech Stack

- **Frontend:** Streamlit
- **Backend:** FastAPI
- **ML Model:** Scikit-learn
- **Others:** Pandas, Pickle, LabelEncoders

---

## 📁 Project Structure

├── backend/ │ └── main.py # FastAPI app ├── frontend/ │ └── app.py # Streamlit app ├── model/ │ ├── model.pkl # Trained model │ ├── label_enc_area.pkl # Label encoder for area │ └── label_enc_item.pkl # Label encoder for crop item ├── requirements.txt └── README.md


---

## 🚀 Getting Started

### 1. Clone the Repo

```bash

git clone https://github.com/your-username/cropxpert.git
cd cropxpert

### Install Dependencies
pip install -r requirements.txt


## Add FastApi backend
cd backend
uvicorn main:app --reload

## Run Streamlit frontend 
cd frontend
streamlit run app.py

Sample Inputs
Area: France
Item: Maize
Year: 2018
Rainfall: 800 mm/year
Temperature: 21°C
Pesticide Usage: 14 tonnes





