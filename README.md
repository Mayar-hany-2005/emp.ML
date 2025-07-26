# emp.ML

# 💼 HR Analytics & Bonus Prediction App

[![Streamlit App](https://img.shields.io/badge/View%20App-Click%20Here-brightgreen)](https://lsedt9m9waq9zartbd7hcc.streamlit.app/)

This is an interactive **HR analytics dashboard** and **bonus prediction app** built with **Streamlit** and **Plotly**, powered by real-world employee datasets.  
You can explore salary trends, analyze department performance, and predict whether an employee is likely to receive a bonus.

---

## 📊 Features

- 🔍 **Business Questions Dashboard**
  - Top salaries in the company
  - Salary growth over time
  - Average tenure per department
  - Salary vs Tenure analysis
  - Department with highest average salary
  - Gender pay gap
  - Titles with highest pay
  - Moved departments tracking
  - Turnover analysis
  - ... and more!

- 🤖 **Bonus Prediction**
  - Enter employee info (salary, department, title, gender, tenure...)
  - Predict if they'll receive a bonus (based on salary increase >5%)
  - Model used: `RandomForestClassifier`

- 📈 **Interactive Charts**
  - Built with `Plotly Express` & `Plotly Graph Objects`
  - Dynamic filtering & auto-updating visuals

---

## 🚀 Try it now

🔗 **Live app**: [Streamlit Cloud](https://lsedt9m9waq9zartbd7hcc.streamlit.app/)

---

## 🧠 Tech Stack

- **Python** (Pandas, Numpy, Scikit-learn)
- **Streamlit** for dashboard GUI
- **Plotly** for interactive charts
- **SMOTE** for balancing classification data
- **Scikit-learn** for model building
- **Google Drive** as a data source



---

## 📌 How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/hr-analytics-bonus-predictor.git
cd hr-analytics-bonus-predictor

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
streamlit run bonus_predict_app.py


