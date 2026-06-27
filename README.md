COVID-19 India Analysis and Risk Assessment Using EDA and Feature Engineering

📌 Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) and Feature Engineering on COVID-19 data from India to uncover trends, compare state-wise pandemic statistics, and assess regional risk levels. Multiple datasets containing COVID-19 cases, testing statistics, and vaccination records are integrated to generate meaningful insights and build a custom COVID Risk Score. Additionally, K-Means Clustering is applied to categorize Indian states into different risk groups.

---

🎯 Objectives

- Analyze COVID-19 trends across Indian states and union territories.
- Study confirmed cases, recoveries, active cases, and deaths.
- Evaluate state-wise testing and vaccination progress.
- Compare Wave 1 and Wave 2 growth patterns.
- Engineer new features for deeper analysis.
- Develop a custom COVID Risk Score.
- Cluster states into High, Moderate, and Low Risk categories using Machine Learning.

---

📂 Datasets Used

1. COVID-19 India Dataset

Contains daily COVID-19 statistics for each state.

Features

- Date
- State/Union Territory
- Confirmed Cases
- Cured Cases
- Deaths

2. State-wise Vaccination Dataset

Features

- State
- Total Doses Administered
- First Dose
- Second Dose

3. State-wise Testing Dataset

Features

- State
- Total Samples Tested
- Positive Cases
- Negative Cases

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

📋 Data Preprocessing

The following preprocessing steps were performed:

- Converted date columns to datetime format.
- Handled missing values using appropriate techniques.
- Standardized inconsistent state names.
- Removed invalid categories such as:
  - Unassigned
  - Cases being reassigned to states
- Cleaned and merged datasets for analysis.

---

📊 Exploratory Data Analysis

The project includes:

- Distribution analysis of confirmed cases, deaths, and vaccinations.
- Correlation analysis between cases, recoveries, deaths, and testing.
- State-wise comparison of pandemic statistics.
- Time-series analysis of COVID-19 waves.
- Trend visualization using line charts, bar charts, and heatmaps.

---

⚙️ Feature Engineering

New features created include:

- Active Cases
- Recovery Rate (%)
- Death Rate (%)
- Positivity Rate (%)
- Active Case Ratio (%)
- Daily New Cases
- Daily Recoveries
- Daily Deaths

These engineered features provide deeper insights into pandemic severity across states.

---

📈 Growth Rate Analysis

Growth analysis was performed separately for:

Wave 1 (2020)

- Average daily increase in confirmed cases.
- State-wise growth comparison.

Wave 2 (2021)

- Higher transmission trends.
- Comparison with Wave 1.

---

🚨 COVID Risk Score

A custom risk metric was developed:

Risk Score = (Death Rate × 0.5) + (Active Case Ratio × 0.3) + (Positivity Rate × 0.2)

The score combines:

- Mortality impact
- Active infection burden
- Testing positivity

Higher scores indicate higher COVID-related risk.

---

🤖 Machine Learning

K-Means Clustering

States were clustered using:

- Confirmed Cases
- Deaths
- Recovery Rate
- Death Rate

Risk Categories:

- 🔴 High Risk
- 🟡 Moderate Risk
- 🟢 Low Risk

---

📌 Key Insights

- COVID-19 spread was concentrated in a few highly populated states.
- Wave 2 was significantly more severe than Wave 1.
- Recovery rates improved over time.
- Increased testing led to better detection of positive cases.
- States showed considerable differences in mortality and recovery performance.
- The custom Risk Score effectively highlighted vulnerable states.
- K-Means clustering successfully grouped states with similar pandemic characteristics.

---



🚀 Future Improvements

- Predict future COVID-19 cases using Machine Learning models.
- Perform time-series forecasting using ARIMA, Prophet, or LSTM.
- Build an interactive Power BI/Tableau dashboard.
- Incorporate demographic and healthcare infrastructure data.
- Deploy the project as an interactive web application.

---

📷 Sample Visualizations

- State-wise Confirmed Cases
- Recovery Rate Comparison
- Death Rate Analysis
- Vaccination Progress
- Testing vs Positive Cases
- COVID Waves Timeline
- Risk Score Ranking
- K-Means Cluster Visualization

---

📜 Conclusion

This project demonstrates how Exploratory Data Analysis, Feature Engineering, and Machine Learning can be combined to analyze pandemic trends and assess regional COVID-19 risk. By integrating case, testing, and vaccination datasets, the analysis provides valuable insights into disease spread, recovery patterns, mortality, and state-wise vulnerability.

