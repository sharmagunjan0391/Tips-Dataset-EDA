# Tips Dataset - Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Tips dataset using Python.

The goal is to understand customer behavior, restaurant bills, tips, party size, smoking status, gender, day, and meal time through different data visualizations.

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📊 Dataset

The dataset contains information about restaurant transactions, including:

* Total Bill
* Tip
* Gender
* Smoker Status
* Day
* Time
* Party Size

## 🔍 EDA Questions

Some of the questions explored in this project are:

1. How is the total bill distributed?
2. How is the tip distributed?
3. Which day has the most transactions?
4. How are transactions distributed between Lunch and Dinner?
5. What is the gender distribution of customers?
6. How is party size distributed?
7. Which day generates the highest average total bill?
8. Which day has the highest average tip?
9. Do smokers or non-smokers pay higher average bills?
10. Does party size affect the total bill?
11. Is there a relationship between total bill and tip?
12. How does total bill vary by day and time?
13. What is the correlation between numerical variables?
14. How does the relationship between total bill and tip vary between Lunch and Dinner?

## 📈 Visualizations Used

The project uses several Seaborn and Matplotlib visualizations:

* Countplot
* Barplot
* Boxplot
* Scatterplot
* Regression Plot
* Heatmap
* JointGrid
* Catplot
* lmplot
* Pairplot
* Pie Chart

## 💡 Key Insights

* Total bill and tip generally have a **positive relationship**.
* Customers with larger bills generally tend to give larger tips.
* Dinner has more transactions than lunch.
* Party size has an effect on the total bill.
* The distribution of bills and tips varies across different days and meal times.
* Smoking status can be compared to understand differences in customer spending behavior.

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/sharmagunjan0391/Tips-Dataset-EDA.git
```

### 2. Open the project folder

```bash
cd Tips-Dataset-EDA
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook Tips_EDA.ipynb
```

## 📁 Project Structure

```text
Tips-Dataset-EDA/
│
├── tips.csv
├── Tips_EDA.ipynb
├── main.py
├── README.md
├── pyproject.toml
├── uv.lock
└── .gitignore
```

## 👩‍💻 Author

**Gunjan Sharma**

This project was created as part of my journey in learning **Python, Data Analysis, and Data Visualization**.
