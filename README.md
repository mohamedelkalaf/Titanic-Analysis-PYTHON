# 🚢 Titanic Survival Prediction (Classification Analysis)

## 📌 Project Overview
This project analyzes the famous **Titanic dataset** to predict passenger survival using **classification models**.  
The goal is to understand which factors (age, gender, class, etc.) were most influential in determining survival.  

---

## 📂 Dataset Description
The dataset contains passenger information with the following key variables:

| Variable     | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| PassengerId  | Unique identifier for each passenger.                                       |
| Pclass       | Ticket class (1st, 2nd, or 3rd class).                                      |
| Survived     | Survival status (1 = survived, 0 = did not survive).                        |
| Name         | Passenger’s full name.                                                      |
| Sex          | Gender of the passenger (male/female).                                      |
| Age          | Passenger’s age (may include missing values).                               |
| SibSp        | Number of siblings/spouses aboard.                                          |
| Parch        | Number of parents/children aboard.                                          |
| Ticket       | Ticket number.                                                              |
| Fare         | Fare paid for the ticket (may include missing values).                      |
| Cabin        | Cabin number (many values missing).                                         |
| Embarked     | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).       |
| Boat         | Lifeboat number (if rescued).                                               |
| Body         | Identification number of recovered body (if applicable).                    |
| Home.Dest    | Passenger’s home destination.                                               |

---

## 🔎 Analysis Workflow
1. **Data Cleaning & Handling Missing Values**  
2. **Exploratory Data Analysis (EDA)** – demographics, class distributions, survival rates  
3. **Feature Engineering** – encoding categorical features, handling missing values  
4. **Classification Modeling** – Logistic Regression, Decision Trees, Random Forest, etc.  
5. **Model Evaluation** – Classification Report & Accuracy  

---

## 📊 Detailed Classification Report
| Metric          | Class 0 (Did Not Survive) | Class 1 (Survived) | Accuracy | Macro Avg | Weighted Avg |
|-----------------|----------------------------|---------------------|----------|-----------|--------------|
| Precision       | 0.7808                     | 0.8056              |          | 0.7932    | 0.7910       |
| Recall          | 0.8906                     | 0.6444              | 0.7890   | 0.7675    | 0.7890       |
| F1-Score        | 0.8321                     | 0.7160              |          | 0.7741    | 0.7842       |
| Support         | 192                        | 135                 | 327      | 327       | 327          |

---

## 🚀 Results
- **Accuracy:** ~78.9%  
- The model performs well in identifying passengers who did **not survive** (high recall = 89%).  
- Predicting survivors is more challenging (recall = 64%).  
- **Key influential features:** Passenger Class, Gender, Age, Fare.  

---

## 📊 Tools & Libraries
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Jupyter Notebook** for analysis and modeling  
- **Classification Models:** Logistic Regression, Random Forest, Decision Tree  

---
bYe
