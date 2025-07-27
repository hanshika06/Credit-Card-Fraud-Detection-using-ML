# Credit-Card-Fraud-Detection-using-ML
This project focuses on detecting fraudulent credit card transactions using machine learning algorithms and visualizing the results with interactive dashboards (Power BI). It builds on core AI/ML models for financial anomaly detection and provides insights to mitigate risks in real-time.

---

## 🔍 Project Overview

Financial fraud detection is essential for minimizing losses and ensuring secure digital transactions. This project uses supervised machine learning techniques to detect fraud in credit card transactions and visualize outcomes using dashboards.

### ✨ Key Features
- Exploratory Data Analysis (EDA)
- Data preprocessing & feature selection
- ML models: Logistic Regression, Decision Tree, Random Forest, etc.
- Model evaluation using accuracy, precision, recall, and F1-score
- Output-ready for Power BI dashboard integration

---

## 📊 Algorithms Used
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost *(optional enhancement)*
- Support Vector Machines *(can be added)*

---

## 🧾 Dataset

- Dataset: [Credit Card Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Contains 284,807 transactions with 492 fraudulent cases.
- Features are PCA-transformed for anonymity.

---

## 🛠️ Tools & Technologies
- Python (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Power BI *(for dashboard visualization)*
- Git & GitHub

---

## 📂 Project Structure

```

├── data/
│   └── creditcard.csv
├── models/
│   ├── logistic\_regression.py
│   ├── decision\_tree.py
│   └── random\_forest.py
├── visualizations/
│   └── fraud\_analysis.ipynb
├── powerbi/
│   └── dashboard.pbix
├── README.md
└── requirements.txt

````

> Note: `powerbi/dashboard.pbix` is where your dashboard file will go.

---

## 📈 Sample Results

- Accuracy: 99.7%
- Precision: 0.91
- Recall: 0.76  
*(Results may vary by model and tuning)*

---

## 📉 Power BI Dashboard *(Coming Soon)*

A Power BI dashboard will be added to provide:
- Fraud vs. Genuine transaction trends
- Time-based fraud heatmaps
- Feature importance visualizations
- Risk probability by transaction ID

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Credit-Card-Fraud-Detection-Using-Machine-Learning.git
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run models:

   ```bash
   python models/logistic_regression.py
   ```
4. Open Power BI file (optional) and explore visuals.

---

## ✅ Future Enhancements

* Add AutoML and deep learning models
* Real-time prediction API (Flask or FastAPI)
* Streamlit frontend integration
* Fully interactive Power BI service dashboard
