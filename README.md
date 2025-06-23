# 🔥 Fire Weather Index (FWI) Prediction App

This project is a **web-based machine learning application** that predicts the **Fire Weather Index (FWI)** using a trained **Ridge Regression** model. It uses the **Flask** framework for backend and serves a modern, responsive HTML frontend for user interaction.

---

## 📌 Features

- 🌡️ Takes 9 key weather-related features as input
- 🧠 Uses a trained ML model to predict FWI
- 🧪 Scales inputs using StandardScaler
- 🎨 Responsive and modern UI
- ✅ Input glossary provided for user clarity
- 🚫 Handles invalid inputs gracefully

---

## 🛠️ Tech Stack

| Component       | Technology Used         |
|----------------|--------------------------|
| Backend         | Python, Flask            |
| Machine Learning| Scikit-learn, Ridge      |
| Frontend        | HTML, CSS                |
| Model Serialization | Pickle              |

---

## 📁 Project Structure

FWI-Predictor/
│
├── application.py # Flask app script
├── models/
│ ├── ridge.pkl # Trained Ridge Regression model
│ └── scaler.pkl # StandardScaler object
├── templates/
│ └── home.html # Frontend UI
└── requirements.txt # Required Python package



---

## 🚀 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/FWI-Predictor.git
cd FWI-Predictor
### 2. Create a Virtual Environment (optional but recommended)
python -m venv venv
On Windows: venv\Scripts\activate
### 3. Install Dependencies
pip install -r requirements.txt
### 4. Run the Application
python application.py

# 🧪 Inputs Glossary
| Field       | Description                      |
| ----------- | -------------------------------- |
| Temperature | Ambient temperature (°C)         |
| RH          | Relative Humidity (%)            |
| Ws          | Wind Speed (km/h)                |
| Rain        | Rainfall (mm)                    |
| FFMC        | Fine Fuel Moisture Code          |
| DMC         | Duff Moisture Code               |
| ISI         | Initial Spread Index             |
| Classes     | Fire occurrence class (e.g. 0/1) |
| Region      | Region code (e.g. 1/2)           |

