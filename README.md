# 🌿 Wellness-Oriented Nutrition Assistant

An intelligent ML-powered nutrition recommendation system for personalized health-based diet planning.

## 📘 Project Overview

The Wellness-Oriented Nutrition Assistant is a machine-learning backed web application that generates personalized diet recommendations based on user data such as:

* Age
* Weight
* Height
* Activity Level
* Dietary Preferences
* Medical Conditions

The system provides smart meal plans, BMR/TDEE calculations, and health-goal–based diets using **Flask + ML models + Python**.

---

## ✨ Features

### ⭐ Core Functionalities

* Personalized meal recommendations
* Diet plans based on BMR, TDEE, and health goals
* ML-based meal plan prediction
* Diabetes & hypertension-aware diet suggestions
* Veg / Non-veg filtering
* Calorie calculation for Weight Loss / Gain / Maintain
* Clean Flask UI (HTML/CSS + Jinja Templates)
* Indian-friendly healthy meal alternatives

---

## 🧠 Tech Stack

**Programming Language:** Python 3.8+

**ML / Data Libraries:** NumPy, Pandas, Scikit-learn, Joblib

**Web Framework:** Flask

**Frontend:** HTML / CSS, Jinja Templates

---

## 🏗️ System Architecture

```
User → Web Form → Flask Backend → ML Model → Calorie/BMR/TDEE calculations → Personalized Meal Plan → UI Output
```

---

## 📂 Project Folder Structure

```
├── app.py
├── model/
│   ├── model.pkl
│   ├── target_encoder.pkl
├── static/
│   ├── style.css
├── templates/
│   ├── index.html
│   ├── result.html
└── README.md
```

---

## ⚙️ Installation & Setup

1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

3️⃣ Run the Flask application

```bash
python app.py
```

4️⃣ Open in browser: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🔍 How It Works

1. User enters:

   * Age, Gender, Height, Weight, Activity Level, Diet Type, Medical Conditions

2. ML model predicts user’s nutrition category

3. System computes:

   * Basal Metabolic Rate (BMR)
   * TDEE
   * Goal-based calorie target

4. Personalized Indian-friendly diet plan is generated

5. UI displays nutrition summary + smart meal plan

---


## 🚀 Future Scope

* Deep learning–based personalized meal generation
* Mobile App (Android/iOS)
* Smart-watch health integration
* Voice-based nutrition assistant
* AI diet chatbot
* Weekly meal planning & auto grocery list generator

---

## 👩‍💻 Authors

* Kavya Godala
* Nigama Vangala
* Ramya Konukati
* Sai Divya Sree Kanaparthi
* Vaishnavi Nandi

**Guide:** Dr. A. Manjula
