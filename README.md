# Term Deposit Campaign Prediction – Modeling in Python

## Overview
This project analyzes the results of a Portuguese bank’s marketing campaign aimed at selling a term deposit product. Using Python for data cleaning, exploration, and machine learning modeling, the goal is to identify factors that influence customer purchase decisions and build predictive models to forecast whether a customer is likely to subscribe to the term deposit.

The work follows the **Data Analytics Workflow**:
1. **Data Cleaning** – Handling missing values, formatting variables, and preparing the dataset.
2. **Exploratory Data Analysis (EDA)** – Understanding trends, relationships, and key factors that affect term deposit purchases.
3. **Modeling** – Training and evaluating two machine learning models to compare performance.
4. **Business Insights** – Interpreting results in a way stakeholders can understand, including implications of false positives and false negatives.

---

## Dataset
The dataset contains customer demographic, financial, and contact information, along with economic indicators. The target variable is `y` – whether the customer subscribed to the term deposit.

**Key columns include**:
- **age** – Age of the customer
- **job**, **marital**, **education** – Demographics
- **housing**, **loan**, **default** – Financial status
- **contact**, **month**, **day_of_week** – Campaign communication details
- **emp.var.rate**, **cons.price.idx**, **cons.conf.idx**, **euribor3m**, **nr.employed** – Economic indicators
- **y** – Target variable (`yes`/`no`)

> See the full data dictionary in the project files.

---

## Project Structure


---

## Methodology
### 1. Exploration
- Generated descriptive statistics for all features  
- Investigated missing values and applied strategies to handle them  
- Explored how customer and economic variables relate to purchase likelihood  

### 2. Modeling
- Model used: **KNN(K Nearest Neighbor)**  
- Assessed impact of selected features  
- Discussed trade-offs between false positives and false negatives  

---

## Results
- Identified **key demographic and economic factors** influencing purchase probability
- Compared two machine learning models, selecting the best-performing one for business use
- Provided **actionable recommendations** for improving future marketing campaigns

---

## Tools
- **Python** – Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Jupyter Notebook** – Development environment
- **Google Docs** – Report preparation

