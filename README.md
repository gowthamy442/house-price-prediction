# house-price-prediction
Predicts median house prices using Linear Regression | Python, scikit-learn, Pandas, Matplotlib
# 🏠 House Price Prediction

A machine learning project that predicts **median house prices** based on features like income, house age, number of rooms, and location using Linear Regression.

---

## 🎯 Objective

To build a regression model that accurately estimates house prices, demonstrating end-to-end ML workflow including data exploration, preprocessing, model training, and evaluation.

---

## 🛠️ Tools & Technologies

| Category | Tools Used |
|----------|-----------|
| Language | Python 3 |
| ML Library | scikit-learn |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Algorithm | Linear Regression |
| Preprocessing | StandardScaler |

---

## 📊 Dataset

- **Name:** California Housing Dataset
- **Source:** Built into scikit-learn (no download needed!)
- **Size:** 20,640 records, 8 features
- **Features:** Median income, house age, average rooms, population, location (lat/long), etc.

---

## ⚙️ How It Works

1. Load the California Housing dataset (built-in)
2. Explore data with visualizations (EDA)
3. Scale features using **StandardScaler**
4. Split data: 80% training, 20% testing
5. Train a **Linear Regression** model
6. Evaluate using RMSE and R² score
7. Predict prices for custom inputs

---

## 📈 Results

| Metric | Value |
|--------|-------|
| Algorithm | Linear Regression |
| R² Score | ~0.60 |
| RMSE | ~0.74 ($74,000) |

> R² of 0.60 means the model explains 60% of price variation — solid for a simple linear model!

---

## 🚀 How to Run

**Step 1: Install dependencies**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

**Step 2: Run the project** (no dataset download needed!)
```bash
python project2_house_price_prediction.py
```

---

## 📁 Project Structure
---

## 💡 Sample Output
---

## 📊 Visualizations Generated

- **House Price Distribution** — histogram of price spread
- **Correlation Heatmap** — which features affect price most
- **Actual vs Predicted** — scatter plot showing model accuracy

---

## 👨‍💻 Author

**Yanamachinthala Gowtham**
BSc Computer Science | Aspiring AI & Cybersecurity Professional
📧 gowthamy442@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/jimmy-undefined-81316a404)

---

## ⚠️ Disclaimer

This project is built for educational purposes as part of learning Machine Learning fundamentals.
