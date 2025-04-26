# 🏏 IPL Score Predictor — 2025

A **Flask-based web application** that predicts the winning probability of a team in an IPL match using a machine learning model trained on historical IPL data!

🌐 **Live Demo:** [ipl-win-prediction-ocgz.onrender.com](https://ipl-win-prediction-ocgz.onrender.com/)

---

## 🚀 Features

✅ Predict the outcome of IPL matches based on real-time input:  
- Select **Batting Team**, **Bowling Team**, and **Venue**  
- Enter **Target**, **Current Score**, **Balls Left**, and **Wickets Down**

✅ Smart Validation:  
- Prevents users from selecting the same team for both batting and bowling.

✅ Clean & Stylish UI:  
- Smooth, modern design with background visuals for an enhanced experience.

---

## 💻 Getting Started (Local Setup)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/rbpata/ipl-win-prediction.git
cd ipl-win-prediction
```

### 2️⃣ Install Dependencies

Make sure you have Python installed, then:

```bash
pip install -r requirements.txt
```

*(If `requirements.txt` is missing, install Flask manually:)*

```bash
pip install flask
```

### 3️⃣ Run the App Locally

```bash
python app.py
```

### 4️⃣ Open in Browser

Navigate to:

```
http://localhost:5000
```

Or check it **live online**:  
👉 [https://ipl-win-prediction-ocgz.onrender.com/](https://ipl-win-prediction-ocgz.onrender.com/)

---

## 🧠 Usage

1. Select the **Batting Team**, **Bowling Team**, and **Venue** from the dropdowns.
2. Enter:
   - 🎯 **Target Score**
   - 🏏 **Current Score**
   - 🕰️ **Balls Left**
   - ❌ **Wickets Down**

3. Click **Predict Winning Probability**.

4. Instantly view the winning probability for both teams!

---

## 📸 Screenshots

| Prediction Form | Prediction Results |
|-----------------|---------------------|
| ![Form Screenshot](https://github.com/rbpata/ipl-win-prediction/blob/master/static/1.png) | ![Results Screenshot](https://github.com/rbpata/ipl-win-prediction/blob/master/static/2.png) |

---

## 💡 Contributing

Contributions, suggestions, and pull requests are welcome!  
If you'd like to help improve this project, feel free to fork and submit a PR.
