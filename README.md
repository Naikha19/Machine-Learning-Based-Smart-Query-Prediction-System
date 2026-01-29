# AgriMind -- Intelligent IoT Agriculture Platform

🚀 **Live Demo:** [Click Here to View Dashboard](https://agriculture-7xjp.onrender.com)

AgriMind is an AI-powered IoT platform designed to help farmers optimize
crop yields and detect sensor anomalies in real time. It integrates a
Python backend (FastAPI + TensorFlow) with a modern React frontend to
deliver actionable agricultural insights.

------------------------------------------------------------------------

## 🧠 Key Features

### 1. Crop & Yield Recommendation Engine

-   **Inputs:** Soil Nitrogen, Temperature, Pesticide Use, Fertilizer
    Amount\
-   **Models Used:**
    -   Random Forest (Crop Classification)\
    -   XGBoost (Yield Regression)\
-   **Outputs:**
    -   Best crop recommendation (e.g., Rice, Coffee, Apples)\
    -   Predicted yield in *hg/ha*

### 2. Real-time IoT Anomaly Detection

-   **Inputs:** 24-hour IoT sensor stream (Moisture, Temperature,
    Humidity)\
-   **Model:** LSTM Autoencoder\
-   **Function:** Detects sensor malfunctions, irrigation leaks, and
    sudden environmental variations.

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   **Frontend:** HTML5, Tailwind CSS, React.js, Chart.js\
-   **Backend:** Python, FastAPI, Uvicorn\
-   **Machine Learning:** TensorFlow (Keras), Scikit-learn, XGBoost,
    Joblib\
-   **Deployment:** Render (Unified Full-Stack Hosting)

------------------------------------------------------------------------

## 📊 Data Sources

Trained using datasets from the **Food and Agriculture Organization
(FAO)**.

-   **Portal:** FAOSTAT\
-   **Domains:** Crop Production, Soil Nutrient Budget, Temperature
    Change

------------------------------------------------------------------------

## 📂 Repository Includes

-   `project.ipynb` Jupyter Notebook\
-   Training scripts, preprocessing pipeline, and model artifacts\
-   Complete frontend + backend source code

------------------------------------------------------------------------

👨‍💻 **Created by:** *Naaman O Jecha*
