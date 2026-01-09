# Titanic-Dataset-Exploratory-Data-Analysis-EDA
This project performs Exploratory Data Analysis (EDA) on the famous Titanic: Machine Learning from Disaster dataset.

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the famous Titanic: Machine Learning from Disaster dataset.
The goal is to understand passenger characteristics, handle missing data, engineer useful features, and analyze factors that influenced survival.

This analysis focuses on data cleaning, visualization, and statistical testing, rather than model building.

## 📂 Dataset

Source: Kaggle – Titanic: Machine Learning from Disaster : https://www.kaggle.com/c/titanic/data

The RMS Titanic, which many called unsinkable, sank on April 15, 1912, after striking an iceberg. More than 1,500 of the 2,224 onboarded people died because there were not enough lifeboats. Survival relied in part on luck, but some groups had a much better chance of living than others.

**Files Used:**
- train.csv
## 🛠️ Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## 🧪 Steps Performed

### 1️⃣ Data Loading
- Imported required libraries  
- Loaded training and test datasets  
- Displayed initial rows for inspection  

---

### 2️⃣ Data Manipulation & Cleaning

#### 🔹 Missing Value Treatment
- **Age:** Filled using the median value  
- **Cabin:** Converted into a binary feature (`Has_Cabin`)  
- **Embarked:** Rows with missing values were removed  

#### 🔹 Duplicate Handling
- Checked for duplicate records  
- Removed duplicates where applicable  

#### 🔹 Feature Engineering
- Created **AgeGroup** (`Child`, `Adult`, `Senior`)  
- Created **FamilySize** feature  
- Created **IsAlone** feature  

#### 🔹 Outlier Analysis
- Used **box plots** to inspect potential outliers  
- Outliers were analyzed carefully and **not blindly removed**

---

### 3️⃣ Exploratory Data Analysis (EDA)
- Descriptive statistics summary  
- Gender distribution analysis  
- Numerical feature distributions (Histogram + KDE)  

#### Survival Analysis By:
- Gender & Passenger Class  
- Age Groups  
- Fare & Cabin availability  
- Family size & Gender  

---

### 4️⃣ Statistical Analysis

#### 🔹 Descriptive Statistics
- Mean, Median, and Mode of:
  - Age  
  - Fare  
  - FamilySize  

#### 🔹 Hypothesis Testing
- **T-test:** Survival vs Gender  
- **ANOVA:** Survival vs Passenger Class  
- **Chi-Squared Test:** Survival vs Age Group  

#### 🔹 Correlation Analysis
- Age  
- Fare  
- FamilySize  
- Has_Cabin  
- IsAlone  
- Survived  

---

## 📊 Key Insights
- Females had significantly higher survival rates than males  
- First-class passengers were more likely to survive  
- Passengers with cabins had better survival probability  
- Smaller families had higher survival chances  
- Age and fare showed meaningful relationships with survival  

---

## 📌 Conclusion
This EDA provides strong evidence that **gender, class, age group, family size, and cabin availability** played major roles in passenger survival.  
The analysis establishes a solid foundation for **feature selection and predictive modeling** in future work.

---

## 👤 Author
**Khan Md Shibli Nomani**
