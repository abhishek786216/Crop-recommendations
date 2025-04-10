# 🌾 Crop Recommendation System

This is a **Streamlit web application** that helps farmers and agricultural planners determine the most suitable crop to grow based on **soil nutrients** and **climatic conditions** using a machine learning model.

🔗 **Live Demo**: [https://crops-rec.streamlit.app/](https://crops-rec.streamlit.app/)

---

## 🚀 How It Works

The app takes the following input from the user:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature (°C)
- Humidity (%)
- pH value
- Rainfall (mm)

It then uses a **pre-trained Random Forest model** to predict the best crop to cultivate under those conditions.

---

## 📦 Requirements

Install the dependencies with:

```bash
pip install -r requirements.txt
