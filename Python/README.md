Student Performance Analysis – Python (Pandas)
📌 Overview

This project explores a student dataset using Python and Pandas to perform data inspection, transformation, and basic statistical analysis.

🎯 Objectives

Inspect dataset structure

Identify missing values

Perform filtering & selection

Create derived features

Analyse distributions & averages

🛠 Tools & Libraries

Python

Pandas

Google Colab

🔎 Data Exploration

Initial inspection of the dataset:

df.info()
df.describe()
df.head()


Purpose:

✔ Understand column types
✔ Detect anomalies
✔ Review sample records

🧹 Missing Value Analysis

Checked for incomplete records:

df.isnull().sum()


This step helps assess data quality before analysis.

🔧 Feature Engineering

Created a derived performance column:

df['passed'] = df['mark'] > 60


Purpose:

✔ Segment student outcomes
✔ Enable categorical comparisons

📊 Key Analysis

Class Distribution

df['class'].value_counts()


Average Score by Gender

df.groupby('gender')['score'].mean()

🧠 Example Insights

Student counts vary across classes

Score patterns differ between groups

Pass/fail segmentation simplifies analysis

Dataset suitable for basic performance evaluation

(Keep honest & simple — recruiters prefer clarity)

✅ Skills Demonstrated

✔ Data loading & inspection
✔ Handling null values
✔ Column selection
✔ GroupBy analysis
✔ Basic feature creation
