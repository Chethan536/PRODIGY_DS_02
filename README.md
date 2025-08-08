# 🛳️ Task-02: Data Cleaning & Exploratory Data Analysis (EDA) on Titanic Dataset

## 📌 Objective
The goal of this task is to perform **data cleaning** and **exploratory data analysis (EDA)** on the Titanic dataset to uncover insights, identify relationships between variables, and detect patterns or trends.

---

## 📂 Dataset
We use the **Titanic dataset** which contains details about passengers, such as:
- Demographics (age, sex)
- Ticket and fare information
- Passenger class
- Survival outcome

**Source:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

---

## ⚙️ Steps Performed

### 1. **Data Loading & Inspection**
- Loaded dataset into Pandas DataFrame
- Checked shape, data types, and basic info
- Reviewed missing values

### 2. **Data Cleaning**
- Dropped `deck` column (too many missing values)
- Filled missing `age` values with **median age**
- Removed any remaining rows with missing values

### 3. **Univariate Analysis**
- **Age Distribution**: Visualized distribution of passengers’ ages
- **Gender Count**: Checked the proportion of male and female passengers

### 4. **Bivariate Analysis**
- **Survival by Gender**: Compared male vs female survival rates
- **Survival by Passenger Class**: Analyzed the impact of class on survival
- **Age vs Fare Scatter Plot**: Explored relationship between ticket price, age, and survival

### 5. **Insights**
- Majority of passengers were aged **20–30**
- **Females had higher survival rates** than males
- **1st class passengers** had a better survival rate than lower classes
- Higher fares were associated with better survival chances

---

## 📊 Visualizations
- **Age Distribution** ![Age Distribution](images/age_distribution.png)
- **Gender Count** ![Gender Count](images/gender_count.png)
- **Survival by Gender** ![Survival by Gender](images/survival_gender.png)
- **Survival by Passenger Class** ![Survival by Class](images/survival_class.png)
- **Age vs Fare Scatter** ![Age vs Fare](images/age_fare_scatter.png)

---

## 🛠️ Technologies Used
- Python 3.x
- Pandas
- Matplotlib
- Seaborn

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/username/repo-name.git
