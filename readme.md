# 🧠 Employee Attrition Prediction – Data Science Project  

## 📌 Overview  
This project analyzes HR data to understand the factors influencing **employee attrition** and builds a **machine learning model** to predict whether an employee is likely to leave the company.  

It demonstrates a complete **data analysis workflow** — from cleaning and visualization to model building, evaluation, and deriving actionable business insights.  

---

## 🎯 Objectives  
- Analyze key HR metrics such as **age, gender, department, and years of service**.  
- Identify major factors contributing to **employee turnover**.  
- Develop a **predictive model** for early attrition detection.  
- Provide actionable insights for HR and management to **improve employee retention**.  

---

## 🧰 Tools & Technologies  

| **Category** | **Tools Used** |
|---------------|----------------|
| **Language** | Python |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| **Environment** | Jupyter Notebook |
| **Visualization** | Power BI *(optional)* |
| **Dataset** | `employee_attrition_data.csv` |

---

## 📊 Data Description  
The dataset contains **10 years of employee data**, including:  
- 👤 Demographics (Age, Gender, Department)  
- 💼 Work Experience (Length of Service, Job Title)  
- 📈 Employment Status (Active, Terminated)  
- 🏢 Business Unit & Termination Reasons  

Each record helps identify the characteristics of employees **most likely to leave** the company.  

---

## ⚙️ Workflow  

### 🔹 1. Data Cleaning  
- Handled missing and duplicate values  
- Converted date columns to proper datetime format  
- Filtered latest records per employee  

### 🔹 2. Exploratory Data Analysis (EDA)  
- Analyzed attrition by **department, age, gender, and service length**  
- Visualized key correlations using **heatmaps and bar charts**  

### 🔹 3. Feature Engineering  
- Encoded categorical columns  
- Created new metrics like **tenure groups** and **service buckets**  

### 🔹 4. Model Building  
- Implemented **Logistic Regression**, **Decision Tree**, and **Random Forest** models  
- Compared models based on **accuracy, precision, recall, and F1-score**  

### 🔹 5. Evaluation & Insights  
- Achieved **~85% accuracy** with Random Forest Classifier  
- Identified top attrition factors:  
  - Shorter length of service  
  - Specific departments (Sales, Manufacturing)  
  - Younger employees  

---

## 📈 Results Summary  

| **Metric** | **Score** |
|-------------|-----------|
| Accuracy | 85% |
| Precision | 83% |
| Recall | 81% |
| F1-Score | 82% |

💡 **Insight:**  
Employees with **shorter tenures** and those in **specific departments** had higher attrition rates, helping HR teams **proactively address retention challenges**.  

---

## 📂 Files Included  

| **File** | **Description** |
|-----------|----------------|
| `Employee Attrition.ipynb` | Main Jupyter Notebook with full analysis and ML model |
| `employee_attrition_data.csv` | HR dataset used for modeling |
| `README.md` | Project documentation (you’re reading it now) |

---

## 💼 Business Impact  
This project enables organizations to:  
- 🔍 Predict which employees are likely to leave early  
- 📊 Improve retention by focusing on key risk factors  
- 💰 Optimize hiring and training costs through data-driven insights  

---

## 🚀 Future Improvements  
- Add **Power BI dashboard** for interactive visual storytelling  
- Deploy model using **Flask** or **Streamlit** web app  
- Integrate **SHAP or LIME** for model explainability  

---

## 👩‍💻 Author  

**Lavi Galav**  
*Data Analyst | Python | SQL | Power BI | Machine Learning*  

📧 **Email:** [lavigalav97@gmail.com]
(mailto:lavigalav97@gmail.com)  

🌐 **GitHub:** [github.com/lavi97_galav](Github) 

💼 **LinkedIn:** [linkedin.com/in/lavigalav](https://linkedin.com/in/lavigalav)  


