🚢 Titanic Dataset - Exploratory Data Analysis (EDA)
📌 Project Overview

This project is part of my CodeAlpha Data Analytics Internship.
The aim of the project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to discover key factors that influenced the survival of passengers.

The Titanic dataset is one of the most popular datasets for data analytics and machine learning practice. It contains demographic and travel-related details of passengers aboard the RMS Titanic. By analyzing this data, we can gain insights into survival patterns and the effect of social and economic status.

📂 Dataset Description

The dataset contains the following key columns:

PassengerId → Unique identifier for each passenger

Survived → Survival status (0 = Did not survive, 1 = Survived)

Pclass → Ticket class (1st, 2nd, or 3rd)

Name → Passenger name

Sex → Gender

Age → Passenger age in years

SibSp → Number of siblings/spouses aboard

Parch → Number of parents/children aboard

Ticket → Ticket number

Fare → Ticket price

Cabin → Cabin number (many values missing)

Embarked → Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

🛠 Tools and Libraries

Python → Programming language

Pandas → Data manipulation and analysis

Matplotlib → Data visualization

Seaborn → Advanced visualization

🔍 Steps Performed

Data Loading

Imported Titanic dataset using Pandas.

Viewed initial rows to understand structure.

Data Exploration

Checked dataset shape, column data types, and summary statistics.

Inspected missing values and duplicate records.

Data Cleaning

Filled missing values in Age with median.

Filled missing values in Embarked with mode.

Dropped Cabin column due to high percentage of missing values.

Exploratory Data Analysis

Univariate analysis (Age distribution, Fare distribution).

Bivariate analysis (Survival by gender, class, family size).

Correlation analysis with heatmap.

Visualization

Created bar charts, histograms, pie chart, and heatmap.

Visualized patterns that influenced survival.

Insights and Conclusion

Derived meaningful insights about survival patterns.

📊 Key Visualizations

Survival by Gender → Women had much higher survival rates than men.

Survival by Passenger Class → 1st class passengers had the highest survival chances.

Age Distribution → Majority of passengers were between 20–40 years.

Fare Distribution → Wealthier passengers (higher fare) had better survival chances.

Family Size vs Survival → Smaller families had higher survival probability.

Correlation Heatmap → Showed relationships between numerical variables (Survived, Age, Fare, Pclass).

✅ Key Insights

Gender: Women had a significantly higher survival rate compared to men.

Class: Passengers in 1st class had much better survival chances than those in 3rd class.

Age: Children had slightly better survival chances than older passengers.

Fare: Passengers who paid higher fares (wealthier) were more likely to survive.

Family Size: Smaller families survived more than large families, likely due to easier evacuation.
