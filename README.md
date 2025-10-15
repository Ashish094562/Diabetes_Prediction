# 🩺 Diabetes Prediction System (Full-Stack ML App)

An end-to-end **Diabetes Prediction Web Application** powered by **Machine Learning**, built with  
🧠 **Python (Flask)** for model inference,  
🚀 **Spring Boot (Java)** for API orchestration, and  
🎨 **React + Vite** for an interactive user interface.

---

## 🌐 Live Demo

| Component | URL |
|------------|------|
| 🧠 **Model API (Flask)** | [https://model-api-3-zbk6.onrender.com](https://model-api-3-zbk6.onrender.com) |
| ⚙️ **Spring Boot Backend** | [https://diabetes-springboot-1.onrender.com](https://diabetes-springboot-1.onrender.com) |
| 💻 **Frontend (React)** | [https://diabetes-web-lime.vercel.app](https://diabetes-web-lime.vercel.app) |
| 🔘 **Database** | using PostgreSQL 17 by render

---

## 🏗️ Project Architecture

```text
Frontend (React + Vite + Tailwind)
           │
           ▼
Spring Boot Backend (Java) ---> Database
           │
           ▼
Model API (Flask + ML Model)
           │
           ▼
Trained ML Model (XGBoost / RandomForest)
```
## 📁 Repository Structure
Repo	Description	Link
🧠 Model API (Python)	Flask app serving ML model predictions.	model-api

⚙️ Spring Boot Backend	Handles routing, CORS, and integrates frontend with model API.	Diabetes_SpringBoot

💻 Frontend (React)	Modern web UI with Vite and Tailwind CSS.	Diabetes_Web

## 🔍 Features

- Real-time diabetes prediction using ML
- Clean UI built with React + Tailwind CSS
- RESTful API with Spring Boot
- Flask microservice hosting the ML model
- Deployed using Render (Backend + Model) and Vercel (Frontend)
- Cross-origin support and secure communication
- Fully modular & extendable architecture

## 🚀 How It Works

- User enters health metrics (Glucose, BMI, Blood Pressure, etc.)

- React frontend sends the input to Spring Boot backend.

- Backend forwards data to Flask model API hosted on Render.

- Flask API loads the trained model → predicts → returns result.

- Backend sends final prediction to the frontend.

- Frontend displays “Diabetic” or “Non-Diabetic” result instantly.

## 🧰 Local Setup Guide
1️⃣ Clone all repositories
```text
git clone https://github.com/Ashish094562/model-api.git
git clone https://github.com/Ashish094562/Diabetes_SpringBoot.git
git clone https://github.com/Ashish094562/Diabetes_Web.git
```
2️⃣ Run Model API (Flask)
```text
cd model-api
pip install -r requirements.txt
python app.py
```
- Runs at: http://localhost:5000

3️⃣ Run Backend (Spring Boot)
```text
cd Diabetes_SpringBoot
mvn spring-boot:run
```

Runs at: http://localhost:8080

4️⃣ Run Frontend (React)
```text
cd Diabetes_Web
npm install
npm run dev
```

- Runs at: http://localhost:5173



## 🧮 Model Details

- Algorithm: XGBoost / Random Forest

- Dataset: PIMA Indians Diabetes Dataset

- Metrics: Accuracy, Precision, Recall, F1-Score

- Focus: Improved minority class performance (diabetic = 1)

- Techniques: Class balancing, threshold tuning, hyperparameter optimization

## 💡 Author

👨‍💻 Ashish Singh
🎓 B.Tech Student | Aspiring Data Scientist | Java & ML Enthusiast
📬 GitHub Profile
