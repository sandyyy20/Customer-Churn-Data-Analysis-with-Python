# 🧩 Customer Data Analysis using Python

## 📘 Overview
This project focuses on analyzing customer data using Python to uncover insights about customer behavior, churn, and service usage.  
The main objective is to clean, explore, and visualize the data to help understand key trends and factors influencing customer churn and satisfaction.  

The project is performed entirely in **Python (Jupyter Notebook)**, showcasing skills in data cleaning, exploratory data analysis (EDA), and visualization.

---

## 📂 Dataset

- **File name:** `Customer data.csv`  
- **Total Rows:** 7043  
- **Total Columns:** 21  
- **Target Column:** `Churn` (Yes/No)  

### 🔑 Key Columns
| Column Name | Description |
|--------------|-------------|
| `customerID` | Unique ID for each customer |
| `gender` | Male/Female |
| `SeniorCitizen` | 1 if senior, else 0 |
| `Partner`, `Dependents` | Relationship-related info |
| `tenure` | Number of months a customer has stayed |
| `PhoneService`, `InternetService` | Type of service used |
| `Contract`, `PaymentMethod` | Billing and subscription details |
| `MonthlyCharges`, `TotalCharges` | Customer billing info |
| `Churn` | Whether the customer left the service |

### 🧹 Data Summary
- No missing or duplicate records after cleaning  
- All numerical and categorical data standardized  
- Converted TotalCharges to numeric for analysis  

---

## ⚙️ Tools and Libraries Used
| Purpose | Library |
|----------|----------|
| Data Handling | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Environment | `Jupyter Notebook` |

---

## 🚀 Steps Followed in the Project

### 1️⃣ Data Loading
- Imported the dataset (`Customer data.csv`) using pandas  
- Checked the basic structure using `df.info()` and `df.describe()`

### 2️⃣ Data Cleaning
- Converted data types for numerical columns  
- Filled missing values appropriately  
- Handled outliers and formatted categorical values  
- Dropped duplicates and unnecessary columns  

### 3️⃣ Exploratory Data Analysis (EDA)
- Analyzed customer demographics (gender, senior citizen, dependents)  
- Visualized internet and phone service distributions  
- Examined monthly charges, total charges, and churn rate  
- Studied relationships between churn and features like contract type, payment method, and tenure  

### 4️⃣ Data Visualization
- Created bar charts, histograms, and heatmaps using matplotlib and seaborn  
- Highlighted key trends in customer churn and retention  

---

## 📊 Results and Insights

✅ Most customers who **use month-to-month contracts** and **electronic check payments** tend to **churn more frequently**.  
✅ **Fiber optic internet users** have a higher churn rate compared to DSL users.  
✅ Longer-tenured customers are **less likely to churn**, showing strong brand loyalty.  
✅ **Senior citizens and single customers** show higher churn tendencies.  

These insights can help improve customer retention strategies, optimize service offerings, and design targeted marketing campaigns.
