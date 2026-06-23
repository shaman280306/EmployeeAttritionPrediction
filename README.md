# 👨‍💼 Employee Attrition Prediction using Machine Learning

## Week 2 Internship Project – XYlofy AI

---

## 📌 Project Information

**Project Title:** Employee Attrition Prediction using Machine Learning

**Intern Name:** Shaman Sharma

**Program:** Bachelor of Technology (B.Tech)

**Branch:** Computer Science Engineering (Artificial Intelligence & Machine Learning)

**University:** Chandigarh University, Punjab, India

**Internship Organization:** XYlofy AI

**Internship Phase:** Week 2 Project Assignment

**Project Domain:** Human Resource Analytics (HR Analytics)

**Project Type:** Machine Learning Classification Project

**Submission Year:** 2026

---

# 🎯 Project Overview

Employee attrition is one of the most significant challenges faced by modern organizations. Losing valuable employees leads to increased recruitment costs, training expenses, reduced productivity, loss of organizational knowledge, and disruption in team performance.

The objective of this project is to develop a Machine Learning-based Employee Attrition Prediction System capable of identifying employees who are likely to leave the organization based on various workplace, compensation, satisfaction, and career-related factors.

Using real-world HR analytics data provided by IBM, this project applies data preprocessing, exploratory data analysis, machine learning classification algorithms, performance evaluation techniques, and business-oriented interpretation to support strategic HR decision-making.

Rather than simply building a predictive model, this project focuses on transforming raw HR data into actionable insights that HR leaders can use to improve employee retention and workforce stability.

---

# 🏢 Business Problem

Organizations often discover attrition only after an employee submits a resignation, leaving limited time for intervention.

Key business questions addressed in this project include:

* Which employees are most likely to leave?
* What factors contribute most strongly to employee attrition?
* Which departments experience the highest turnover?
* Does salary significantly impact attrition?
* How can HR proactively reduce employee exits?

The answers to these questions enable organizations to shift from reactive workforce management to proactive retention planning.

---

# 📂 Dataset Information

### Dataset Source

IBM HR Analytics Employee Attrition Dataset

### Dataset Characteristics

* Total Employees: 1,470
* Real-world HR Analytics dataset
* Structured employee information
* Mix of categorical and numerical features
* Binary target variable

### Target Variable

**Attrition**

* Yes = Employee Left
* No = Employee Stayed

After preprocessing:

* 1 = Employee Left
* 0 = Employee Stayed

---

# 🛠 Technologies & Tools Used

| Technology   | Purpose                           |
| ------------ | --------------------------------- |
| Python       | Core Programming Language         |
| Google Colab | Development Environment           |
| Pandas       | Data Processing                   |
| NumPy        | Numerical Operations              |
| Scikit-Learn | Machine Learning Models           |
| Matplotlib   | Visualization                     |
| Seaborn      | Statistical Visualization         |
| GitHub       | Version Control & Project Hosting |

---

# ⚙️ Machine Learning Workflow

## 1️⃣ Data Loading & Exploration

The dataset was loaded using Pandas and explored to understand:

* Dataset dimensions
* Feature types
* Target variable distribution
* Numerical vs categorical features
* Initial business observations

This step provided an understanding of workforce composition and attrition patterns.

---

## 2️⃣ Data Cleaning & Preprocessing

Several preprocessing techniques were applied:

### Missing Value Handling

Checked for null values and ensured dataset consistency.

### Feature Removal

Removed non-informative attributes such as:

* EmployeeNumber
* Over18
* StandardHours

### Target Encoding

Converted:

* Yes → 1
* No → 0

### One-Hot Encoding

Applied to categorical variables including:

* Department
* JobRole
* BusinessTravel
* MaritalStatus
* EducationField

### Feature Scaling

StandardScaler was used to normalize numerical features and improve model performance.

---

## 3️⃣ Exploratory Data Analysis (EDA)

The project investigated attrition patterns across multiple business dimensions.

### Areas Analyzed

* Attrition by Department
* Attrition by Job Role
* Attrition by Monthly Income
* Attrition by Work-Life Balance
* Attrition by Years at Company

The analysis revealed meaningful workforce trends and helped identify employee groups requiring retention attention.

---

## 4️⃣ Machine Learning Models

Three classification algorithms were implemented and compared.

### Logistic Regression

Used as the baseline model.

Advantages:

* Highly interpretable
* HR-friendly explanations
* Fast training

---

### Random Forest Classifier

Ensemble learning model based on multiple decision trees.

Advantages:

* Handles complex relationships
* Robust performance
* Feature importance extraction

---

### Gradient Boosting Classifier

Advanced boosting algorithm designed to improve predictive accuracy.

Advantages:

* Strong predictive capability
* Effective on structured business datasets

---

# 📊 Model Evaluation Metrics

Models were evaluated using industry-standard classification metrics:

### Precision

Measures prediction accuracy for attrition cases.

### Recall

Measures ability to identify employees likely to leave.

### F1 Score

Balances Precision and Recall.

### ROC-AUC Score

Measures overall classification effectiveness.

### Confusion Matrix

Provides detailed classification results.

The best-performing model was selected based on its overall predictive effectiveness and practical business usability.

---

# 📈 Visualizations Included

### Chart 1

Employee Attrition Distribution

### Chart 2

Monthly Income vs Attrition

### Chart 3

Confusion Matrix Heatmap

### Chart 4

Top 10 Feature Importance Analysis

### Chart 5 (Bonus)

ROC Curve Comparison

These visualizations help communicate insights to both technical and non-technical stakeholders.

---

# 🔍 Feature Importance Analysis

One of the most valuable aspects of this project is identifying the factors that contribute most strongly to employee attrition.

Feature importance analysis allows HR teams to:

* Understand attrition drivers
* Prioritize intervention efforts
* Allocate retention budgets effectively
* Design targeted employee engagement programs

The project ranks the most influential variables contributing to employee exits and translates those findings into business recommendations.

---

# 💡 Key Business Insights

The analysis suggests that employee attrition is influenced by multiple interconnected factors rather than salary alone.

Key themes include:

* Employee satisfaction
* Career growth opportunities
* Work-life balance
* Compensation
* Job role characteristics
* Organizational tenure

The findings demonstrate that proactive employee engagement strategies can significantly reduce workforce turnover.

---

# 📋 Business Recommendations

### Recommendation 1

Implement targeted retention programs for employees identified as high-risk by the predictive model.

### Recommendation 2

Conduct regular career progression and engagement discussions with employees showing early attrition indicators.

### Recommendation 3

Improve work-life balance initiatives and employee wellness programs.

### Recommendation 4

Use predictive HR analytics dashboards to continuously monitor workforce stability.

---

# 🚀 Learning Outcomes

Through this project, I strengthened my practical understanding of:

* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis
* Classification Algorithms
* Model Evaluation
* HR Analytics
* Business Intelligence
* Machine Learning Deployment Workflow
* Data-Driven Decision Making

---

# 👨‍💻 About the Author

### Shaman Sharma

B.Tech Computer Science Engineering (Artificial Intelligence & Machine Learning)

Chandigarh University, Punjab, India

Areas of Interest:

* Artificial Intelligence
* Machine Learning
* Data Science
* Software Development
* Research & Innovation
* Predictive Analytics
* Intelligent Systems

---

## 🏆 Internship Project Submission

**Organization:** XYlofy AI

**Project:** Employee Attrition Prediction using Machine Learning

**Internship Assignment:** Week 2

**Submitted By:** Shaman Sharma

*"Transforming HR data into actionable workforce intelligence through Machine Learning."*
