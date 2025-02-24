# **Employee Attrition Prediction - HR Analytics Project**

## **Overview**
Employee attrition is a key challenge for organizations, leading to increased hiring costs, productivity losses, and operational disruptions. This project focuses on analyzing employee churn trends using **exploratory data analysis (EDA)** and **machine learning models** to predict attrition. The findings offer actionable insights for HR teams to improve retention strategies and create a more stable workforce.

## **Project Structure**
```
📂 Employee-Attrition-Prediction
│── 📁 data                 # Dataset used for analysis
│── 📁 notebooks            # Jupyter Notebooks for EDA & model training
│── 📁 reports              # Generated visualizations and insights
│── 📁 models               # Saved machine learning models
│── README.md              # Project documentation
│── requirements.txt       # Required Python packages
│── eda.py                 # Exploratory Data Analysis script
│── model_training.py      # Machine Learning Model training
│── hr_attrition_report.pdf # Comprehensive report for HR
```

## **Dataset Information**
The dataset consists of **1,470 employees** with **35 features**, including:
- **Demographics:** Age, Gender, Marital Status, etc.
- **Job-Related Features:** Department, Job Role, Work Experience, Monthly Income
- **Workplace Factors:** Distance from Home, Overtime, Business Travel, Work-Life Balance
- **Attrition Label:** Whether the employee has left the company (Yes/No)

## **Exploratory Data Analysis (EDA)**
EDA was conducted to identify patterns and key factors influencing attrition. The following visualizations were created:
- **Attrition Distribution:** Understanding the proportion of employees leaving.
- **Salary vs Attrition:** Identifying income groups with higher churn.
- **Age vs Attrition:** Assessing attrition trends among different age groups.
- **Department-wise Attrition:** Identifying departments with the highest churn.
- **Business Travel & Work-Life Balance Impact:** Evaluating their effect on attrition rates.

## **Machine Learning Model**
A **Logistic Regression** model was trained to predict employee attrition. The model was optimized using:
- **Feature Engineering:** Encoding categorical variables and scaling numerical features.
- **Handling Imbalanced Data:** SMOTE (Synthetic Minority Over-sampling Technique) was applied.
- **Hyperparameter Tuning:** GridSearchCV was used to fine-tune model parameters.

### **Model Performance**
| Metric       | Score  |
|-------------|--------|
| Accuracy    | 80%    |
| Precision   | 73%    |
| Recall      | 74%    |

The model achieved a **balanced precision-recall tradeoff**, ensuring HR can correctly identify at-risk employees without excessive false positives.

## **Key Insights & Recommendations**
✔ **Low Salary Increases Attrition:** Employees earning below **$5,000/month** show significantly higher churn. HR should consider **salary adjustments and performance-based incentives**.

✔ **Younger Employees Leave More:** The **20-30 age group** has the highest attrition, indicating a need for **career growth programs and mentorship**.

✔ **High Churn in Sales & R&D Departments:** These teams experience the **most resignations**, requiring better **leadership support and workload balance**.

✔ **Work-Life Balance & Travel Impact:** Employees with **poor work-life balance and frequent business travel** tend to leave more. HR should **optimize travel 
policies and promote hybrid work models**.

## **How to Use This Project**
1️⃣ **Clone the Repository**
```bash
git clone https://github.com/your_username/Employee-Attrition-Prediction.git
cd Employee-Attrition-Prediction
```

2️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

3️⃣ **Run EDA**
```bash
python eda.py
```

4️⃣ **Train the Model**
```bash
python model_training.py
```

5️⃣ **Review HR Report**
Check `hr_attrition_report.pdf` for insights and recommendations.


## **Contributors**
- **Your Name** - Mohit Kumar
- **Open for Contributions!** Feel free to fork and improve the model.

## **License**
This project is licensed under the **MIT License**.

---
### ⭐ If you found this project useful, give it a star on GitHub! ⭐

