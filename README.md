# 🍎 FreshGuard AI: Food Spoilage Predictor

An interactive Machine Learning web application that predicts whether stored food is **Fresh** or **Spoiled** based on environmental sensor readings (**Temperature**, **Humidity**, and **Gas PPM**). Built as the AI analytics layer for the **FreshGuard IoT Smart Fruit Bowl** system.

---

## 🚀 Features
- **Real-Time AI Prediction:** Instant freshness classification with confidence percentage.
- **Random Forest Classifier:** Trained on environmental telemetry (Temperature °C, Humidity %, and MQ-135 Gas PPM).
- **Interactive Web UI:** Built with Streamlit sliders to simulate live IoT sensor inputs.

---

## 🛠️ Tech Stack
- **Language:** Python
- **Machine Learning:** Scikit-Learn (`RandomForestClassifier`)
- **Data Manipulation:** Pandas
- **Web Framework:** Streamlit

---

## 📂 Project Structure
```text
FreshGuard-AI-Predictor/
├── app.py              # Main Streamlit web app & ML model training script
├── sensor_data.csv     # Environmental dataset (Temperature, Humidity, Gas_PPM, Status)
├── requirements.txt    # Python dependencies for deployment
└── README.md           # Project documentation
```

---

## 💻 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/kulathungasadew15/FreshGuard-AI-Predictor.git](https://github.com/kulathungasadew15/FreshGuard-AI-Predictor.git)
   cd FreshGuard-AI-Predictor
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

---

## 👤 Author
**Sadew Kulathunga**
- LinkedIn: [Sadew Kulathunga](https://www.linkedin.com/in/sadew-kulathunga-5496b8411)
