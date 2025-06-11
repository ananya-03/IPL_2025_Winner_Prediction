# 🏏 IPL 2025 Winner Prediction using Machine Learning

**Will Punjab Kings be the IPL 2025 Champion?**  
Or so says my machine learning model! 😄

This project is an end-to-end pipeline that forecasts IPL match outcomes using historical match and ball-by-ball data, with **XGBoost** as the final winning model. With over **92% accuracy**, the model simulates future matches and predicts possible season outcomes.

---

## 📌 Project Highlights

### ✅ Data Preparation & Feature Engineering
- Merged match-level and ball-by-ball datasets (2008–2024).
- Engineered impactful features:
  - **Powerplay Runs**, **Wickets Lost**
  - **Net Run Difference**
  - **Venue-Specific Win Rates**
  - **Toss Win Impact** and more.

### 📊 Exploratory Data Analysis
- Visualized:
  - Toss influence on outcomes
  - Home advantage
  - Team-wise season performance trends

### 🧼 Preprocessing & Modeling
- Encoded categorical features
- Scaled numerical features
- Trained:
  - Logistic Regression
  - Random Forest
  - XGBoost (Best performer!)

### 🔮 2025 Season Simulation
- Simulated key match features for IPL 2025 using historical distributions:
  - Toss winner & decision
  - Total runs
  - Opponent matchup context
- Predicted match outcomes using the trained model.
- 🏆 **Punjab Kings emerged as the most probable winner (96.6% confidence)**

> ⚠️ **Note:** This was a fun side project! No actual 2025 match data was used — the goal was to experiment with predictive modeling, not to claim a definitive outcome.

---

## 💡 Technologies Used

- `Python`
- `Pandas`, `NumPy`
- `Matplotlib`, `Seaborn`
- `Scikit-learn`
- `XGBoost`
- `SHAP` (for model explainability)

---


---

## 📍 Future Improvements

- Integrate live scraping to fetch 2025 match stats
- Create a web dashboard using `Streamlit` or `Plotly Dash`
- Tune simulation logic with Monte Carlo methods

---

## 🙋‍♀️ About Me

Hi! I'm **Ananya**, a data science enthusiast exploring the intersection of sports, machine learning, and storytelling. If this project interests you, feel free to [connect](https://www.linkedin.com/in/ananya-singh-7b55a51ab/) or shoot me a message!

---

## 📬 Contact

- 🌐 Website: [AnanyaSingh/PersonalPortfolio.com](https://ananya-03.github.io/PersonalPortfolio/)

- 🔗 LinkedIn: [Ananya Singh](https://www.linkedin.com/in/ananya-singh-7b55a51ab/)  

- 🐍 GitHub: [@ananya-03](https://github.com/ananya-03)


---

## ⭐ If you found this interesting...

Give the repo a ⭐, fork it, or try building your own season simulator!


