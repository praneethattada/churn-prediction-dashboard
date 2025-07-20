
# 🧠 Churn Prediction Dashboard

An interactive machine learning dashboard built with **Streamlit** to predict customer churn based on user profile features. This tool empowers **product** and **marketing** teams to identify at-risk customers and take **proactive retention actions** that could save **₹12+ Lakh in monthly GMV**.

<p align="center">
  <img src="streamlit-app.gif" alt="App Demo" width="80%"/>
</p>

---

## 🚀 Key Features

- 🔍 **Real-time churn prediction** using user inputs  
- 🖱️ **Interactive UI** with dropdowns, sliders, and instant feedback  
- 🤖 Supports multiple ML models:  
  - Logistic Regression  
  - Random Forest Classifier  
- 📈 Achieved **ROC AUC ≥ 0.88** on test data  
- 💰 Simulated business impact: Significant retention ROI  

---

## 🛠 Tech Stack

| Layer         | Tools Used                                  |
|---------------|---------------------------------------------|
| **Frontend**  | [Streamlit](https://streamlit.io)           |
| **Backend**   | Python, Scikit-learn, Pandas, NumPy         |
| **Modeling**  | Logistic Regression, Random Forest          |
| **Notebook**  | Jupyter Notebook for experimentation        |

---

## 📈 Model Performance

Trained on a preprocessed version of the **Telco Customer Churn Dataset**.

| Metric         | Value        |
|----------------|--------------|
| ROC AUC        | ≥ 0.88       |
| Model Type     | Classification |
| Evaluation     | Confusion matrix, ROC curve, Precision/Recall |

Explore all metrics and visualizations in `churn_prediction.ipynb`.

---

## 📂 Project Structure

```

.
├── app.py                     # Streamlit frontend app
├── churn\_prediction.ipynb     # Model training & evaluation notebook
├── churn\_model.pkl            # Trained ML model (serialized)
├── requirements.txt           # Project dependencies
├── streamlit-app.gif          # Demo animation (optional)
└── README.md                  # Project documentation

````

---

## 💻 Run the App Locally

```bash
# Clone the repository
git clone https://github.com/praneethattada/churn-prediction-dashboard.git
cd churn-prediction-dashboard

# Install Python dependencies
pip install -r requirements.txt

# Launch the Streamlit dashboard
streamlit run app.py
````

---

## 📊 Business Impact

> **Scenario**: If 2% of your customer base is likely to churn each month, and your average GMV per customer is ₹5,000, targeting high-risk users could retain ₹12+ Lakh in monthly GMV.

Use this dashboard to experiment with **what-if scenarios**, **feature importance**, and **threshold tuning** to align interventions with business goals.

---

## 🧠 Dataset Reference

Modified version of [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn) — includes demographic, service, and account features.


